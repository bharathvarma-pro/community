<!---
This is an autogenerated file!

Please do not edit this file directly, but instead make changes to the
sigs.yaml file in the project root.

To understand how this file is generated, see https://git.k8s.io/community/generator/README.md
--->
# Scalability Special Interest Group

SIG Scalability is responsible for defining and driving scalability goals for Kubernetes. We also coordinate and contribute to general system-wide scalability and performance improvements (not falling into the charter of other individual SIGs) by driving large architectural changes and finding bottlenecks, as well as provide guidance and consultations about any scalability and performance related aspects of Kubernetes. <br/> We are actively working on finding and removing various scalability bottlenecks which should lead us towards pushing system's scalability higher. This may include going beyond 5k nodes in the future - although that's not our priority as of now, this is very deeply in our area of interest and we are happy to guide and collaborate on any efforts towards that goal as long as they are not sacrificing on overall Kubernetes architecture (by making it non-maintainable, non-understandable, etc.).

The [charter](charter.md) defines the scope and governance of the Scalability Special Interest Group.

## Meetings
* Regular SIG Meeting: [Thursdays at 18:30 Warsaw](https://docs.google.com/document/d/1FQx0BPlkkl1Bn0c9ocVBxYIKojpmrS1CFP5h0DI68AE/edit) (bi-weekly ([upcoming meeting dates](#upcoming-2019-meeting-dates))). [Convert to your timezone](http://www.thetimezoneconverter.com/?t=18:30&tz=Warsaw).
  * [Meeting notes and Agenda](https://docs.google.com/a/bobsplanet.com/document/d/1hEpf25qifVWztaeZPFmjNiJvPo-5JX1z0LSvvVY5G2g/edit?usp=drive_web).
  * [Meeting recordings](https://www.youtube.com/watch?v=NDP1uYyom28&list=PL69nYSiGNLP2X-hzNTqyELU6jYS3p10uL).

## Leadership

### Chairs
The Chairs of the SIG run operations and processes governing the SIG.

* Shyam Jeedigunta (**[@shyamjvs](https://github.com/shyamjvs)**), AWS
* Wojciech Tyczynski (**[@wojtek-t](https://github.com/wojtek-t)**), Google

## Contact
- Slack: [#sig-scalability](https://kubernetes.slack.com/messages/sig-scalability)
- [Mailing list](https://groups.google.com/forum/#!forum/kubernetes-sig-scale)
- [Open Community Issues/PRs](https://github.com/kubernetes/community/labels/sig%2Fscalability)
- GitHub Teams:
    - [@kubernetes/sig-scalability-api-reviews](https://github.com/orgs/kubernetes/teams/sig-scalability-api-reviews) - API Changes and Reviews
    - [@kubernetes/sig-scalability-bugs](https://github.com/orgs/kubernetes/teams/sig-scalability-bugs) - Bug Triage and Troubleshooting
    - [@kubernetes/sig-scalability-feature-requests](https://github.com/orgs/kubernetes/teams/sig-scalability-feature-requests) - Feature Requests
    - [@kubernetes/sig-scalability-misc](https://github.com/orgs/kubernetes/teams/sig-scalability-misc) - General Discussion
    - [@kubernetes/sig-scalability-pr-reviews](https://github.com/orgs/kubernetes/teams/sig-scalability-pr-reviews) - PR Reviews
    - [@kubernetes/sig-scalability-proprosals](https://github.com/orgs/kubernetes/teams/sig-scalability-proprosals) - Design Proposals
    - [@kubernetes/sig-scalability-test-failures](https://github.com/orgs/kubernetes/teams/sig-scalability-test-failures) - Test Failures and Triage

## Subprojects

The following [subprojects][subproject-definition] are owned by sig-scalability:
### kubernetes-scalability-and-performance-tests-and-validation
[Described below](#kubernetes-scalability-and-performance-tests-and-validation)
- **Owners:**
  - https://raw.githubusercontent.com/kubernetes/community/master/sig-scalability/processes/OWNERS
  - https://raw.githubusercontent.com/kubernetes/kubernetes/master/test/e2e/scalability/OWNERS
### kubernetes-scalability-bottlenecks-detection
[Described below](#kubernetes-scalability-bottlenecks-detection)
- **Owners:**
  - https://raw.githubusercontent.com/kubernetes/community/master/sig-scalability/blogs/OWNERS
### kubernetes-scalability-definition
[Described below](#kubernetes-scalability-definition)
- **Owners:**
  - https://raw.githubusercontent.com/kubernetes/community/master/sig-scalability/configs-and-limits/OWNERS
  - https://raw.githubusercontent.com/kubernetes/community/master/sig-scalability/slos/OWNERS
### kubernetes-scalability-governance
[Described below](#kubernetes-scalability-governance)
- **Owners:**
  - https://raw.githubusercontent.com/kubernetes/community/master/sig-scalability/governance/OWNERS
### kubernetes-scalability-test-frameworks
[Described below](#kubernetes-scalability-test-frameworks)
- **Owners:**
  - https://raw.githubusercontent.com/kubernetes/kubernetes/master/cluster/images/kubemark/OWNERS
  - https://raw.githubusercontent.com/kubernetes/kubernetes/master/cmd/kubemark/OWNERS
  - https://raw.githubusercontent.com/kubernetes/kubernetes/master/pkg/kubemark/OWNERS
  - https://raw.githubusercontent.com/kubernetes/kubernetes/master/test/kubemark/OWNERS
  - https://raw.githubusercontent.com/kubernetes/perf-tests/master/OWNERS
  - https://raw.githubusercontent.com/kubernetes/perf-tests/master/clusterloader2/OWNERS

[subproject-definition]: https://github.com/kubernetes/community/blob/master/governance.md#subprojects
<!-- BEGIN CUSTOM CONTENT -->
# Scalability Regression - Contact Points

*Reach out to these folks if you have any inquiries about scalability regressions, e.g.
regression status, whether it should block the release or not, etc.*

* Janek Lukasiewicz (**[@oxddr](https://github.com/oxddr)**), Google
* Krzysztof Siedlecki (**[@krzysied](https://github.com/krzysied)**), Google
* Maciej Borsz (**[@mborsz](https://github.com/mborsz)**), Google
* Matt Matejczyk (**[@mm4tt](https://github.com/mm4tt)**), Google
* Wojciech Tyczynski (**[@wojtek-t](https://github.com/wojtek-t)**), Google

## Upcoming 2019 Meeting Dates
   * 07/04
   * 07/18
   * 08/01
   * 08/15
   * 08/29
   * 09/12
   * 09/26
   * 10/10
   * 10/24
   * 11/07
   * 11/21
   * 12/05
   * 12/19

# Details about SIG-Scalability sub-projects

## Kubernetes scalability definition

Defining what does it mean that "Kubernetes scales".
This includes defining (or approving) individual performance and scalability
related SLIs/SLOs, ensuring they are all oriented on user experience and
consistent with each other.

Measuring and publishing limits within which Kubernetes is supposed to scale
as defined above and providing recommendations about setting clusters in
scalable and performant ways.

* [Kubernetes Scalability SLIs/SLOs](./slos/slos.md).

## Kubernetes scalability governance

Establishing and documenting best practises on how do design and implement
Kubernetes features in scalable and performance way.
Educating contributors and ensuring best practises are widely used.

* [Regressions case study](./governance/scalability-regressions-case-studies.md)

## Kubernetes scalability test frameworks

Designing and creating frameworks to make scalability and performance testing
of Kubernetes easy and available for all contributors.
Different frameworks may help in different aspects of scalability testing,
enabling making conscious tradeoffs, e.g. cost vs accuracy or real life vs
more generalized benchmarking scenarios.

* [Cluster Loader v2](https://github.com/kubernetes/perf-tests/tree/master/clusterloader2)
* [Kubemark](https://github.com/kubernetes/kubernetes/blob/master/cmd/kubemark)

## Kubernetes scalability and performance tests and validation

Ensuring that all tests necessary to validate Kubernetes scalability and
performance exists (ideally by providing easy-to-use frameworks and working
with SIGs to provide them), having engironment and resources to run them.

Ensuring that tests are being executed according to calendar and ensuring that
each official Kubernetes release satisfies all scalability and performance
requirements as stated in "Kubernetes scalability" definition.
This also includes designing processes to reduce maintenance work and number
of scalability and performance regressions:

* [Processes](https://github.com/kubernetes/community/tree/master/sig-scalability/processes)

We are in progress to migrating tests to new framework:

* [Still official tests](https://github.com/kubernetes/kubernetes/tree/master/test/e2e/scalability)
* [Soon to be official tests](https://github.com/kubernetes/perf-tests/tree/master/clusterloader2/testing)

## Kubernetes scalability bottlenecks detection

Detecting scalability bottlenecks and limitations, documenting them and
driving architectural changes to eliminate those (if such are required) in
collaboration with other SIGs or directly delegating improvements to
individual SIGs, of bottlenecks aren't cross-cutting the whole system.

* [Scalability issues with Services](.blogs/k8s-services-scalability-issues.md)

<!-- END CUSTOM CONTENT -->