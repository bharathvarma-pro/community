<!---
This is an autogenerated file!

Please do not edit this file directly, but instead make changes to the
sigs.yaml file in the project root.

To understand how this file is generated, see https://git.k8s.io/community/generator/README.md
--->
# Cloud Provider Special Interest Group

Ensures that the Kubernetes ecosystem is evolving in a way that is neutral to all (public and private) cloud providers. It will be responsible for establishing standards and requirements that must be met by all providers to ensure optimal integration with Kubernetes.

The [charter](CHARTER.md) defines the scope and governance of the Cloud Provider Special Interest Group.

## Meetings
* Regular SIG Meeting: [Wednesdays at 1:00 PT (Pacific Time)](https://docs.google.com/document/d/1FQx0BPlkkl1Bn0c9ocVBxYIKojpmrS1CFP5h0DI68AE/edit) (biweekly). [Convert to your timezone](http://www.thetimezoneconverter.com/?t=1:00&tz=PT%20%28Pacific%20Time%29).
  * [Meeting notes and Agenda](https://docs.google.com/document/d/1OZE-ub-v6B8y-GuaWejL-vU_f9jsjBbrim4LtTfxssw/edit#heading=h.w7i4ksrweimp).
  * [Meeting recordings](https://www.youtube.com/playlist?list=PL69nYSiGNLP3dXLcYbRKCbpPCN-8CDFAB).

## Leadership

### Chairs
The Chairs of the SIG run operations and processes governing the SIG.

* Andrew Sy Kim (**[@andrewsykim](https://github.com/andrewsykim)**), VMware
* Walter Fender (**[@cheftako](https://github.com/cheftako)**), Google
* Chris Hoge (**[@hogepodge](https://github.com/hogepodge)**), OpenStack Foundation

## Emeritus Leads

* Jago Macleod (**[@jagosan](https://github.com/jagosan)**), Google

## Contact
- Slack: [#sig-cloud-provider](https://kubernetes.slack.com/messages/sig-cloud-provider)
- [Mailing list](https://groups.google.com/forum/#!forum/kubernetes-sig-cloud-provider)
- [Open Community Issues/PRs](https://github.com/kubernetes/community/labels/sig%2Fcloud-provider)
- GitHub Teams:
    - [@kubernetes/sig-cloud-provider-api-reviews](https://github.com/orgs/kubernetes/teams/sig-cloud-provider-api-reviews) - API Changes and Reviews
    - [@kubernetes/sig-cloud-provider-bugs](https://github.com/orgs/kubernetes/teams/sig-cloud-provider-bugs) - Bug Triage and Troubleshooting
    - [@kubernetes/sig-cloud-provider-feature-requests](https://github.com/orgs/kubernetes/teams/sig-cloud-provider-feature-requests) - Feature Requests
    - [@kubernetes/sig-cloud-provider-maintainers](https://github.com/orgs/kubernetes/teams/sig-cloud-provider-maintainers) - Cloud Providers Maintainers
    - [@kubernetes/sig-cloud-provider-pr-reviews](https://github.com/orgs/kubernetes/teams/sig-cloud-provider-pr-reviews) - PR Reviews
    - [@kubernetes/sig-cloud-provider-proposals](https://github.com/orgs/kubernetes/teams/sig-cloud-provider-proposals) - Design Proposals
    - [@kubernetes/sig-cloud-provider-test-failures](https://github.com/orgs/kubernetes/teams/sig-cloud-provider-test-failures) - Test Failures and Triage
    - [@kubernetes/sig-cloud-providers-misc](https://github.com/orgs/kubernetes/teams/sig-cloud-providers-misc) - General Discussion

## Subprojects

The following [subprojects][subproject-definition] are owned by sig-cloud-provider:
### cloud-provider-extraction-migration
- **Owners:**
  - https://raw.githubusercontent.com/kubernetes-sigs/apiserver-network-proxy/master/OWNERS
  - https://raw.githubusercontent.com/kubernetes/community/master/sig-cloud-provider/cloud-provider-extraction-migration/OWNERS
  - https://raw.githubusercontent.com/kubernetes/legacy-cloud-providers/master/OWNERS
- **Meetings:**
  - Weekly Sync removing the in-tree cloud providers led by @cheftako and @mcrute: [Thursdays at 13:30 PT (Pacific Time)](https://docs.google.com/document/d/1KLsGGzNXQbsPeELCeF_q-f0h0CEGSe20xiwvcR2NlYM/edit) (weekly). [Convert to your timezone](http://www.thetimezoneconverter.com/?t=13:30&tz=PT%20%28Pacific%20Time%29).
### kubernetes-cloud-provider
- **Owners:**
  - https://raw.githubusercontent.com/kubernetes/cloud-provider-sample/master/OWNERS
  - https://raw.githubusercontent.com/kubernetes/cloud-provider/master/OWNERS
  - https://raw.githubusercontent.com/kubernetes/kubernetes/master/cmd/cloud-controller-manager/OWNERS
  - https://raw.githubusercontent.com/kubernetes/kubernetes/master/pkg/cloudprovider/OWNERS
  - https://raw.githubusercontent.com/kubernetes/kubernetes/master/pkg/controller/cloud/OWNERS
  - https://raw.githubusercontent.com/kubernetes/kubernetes/master/staging/src/k8s.io/cloud-provider/OWNERS
### provider-alibaba-cloud
- **Owners:**
  - https://raw.githubusercontent.com/kubernetes-sigs/alibaba-cloud-csi-driver/master/OWNERS
  - https://raw.githubusercontent.com/kubernetes/cloud-provider-alibaba-cloud/master/OWNERS
### provider-aws
- **Owners:**
  - https://raw.githubusercontent.com/kubernetes-sigs/aws-alb-ingress-controller/master/OWNERS
  - https://raw.githubusercontent.com/kubernetes-sigs/aws-ebs-csi-driver/master/OWNERS
  - https://raw.githubusercontent.com/kubernetes-sigs/aws-efs-csi-driver/master/OWNERS
  - https://raw.githubusercontent.com/kubernetes-sigs/aws-encryption-provider/master/OWNERS
  - https://raw.githubusercontent.com/kubernetes-sigs/aws-fsx-csi-driver/master/OWNERS
  - https://raw.githubusercontent.com/kubernetes-sigs/aws-iam-authenticator/master/OWNERS
  - https://raw.githubusercontent.com/kubernetes/cloud-provider-aws/master/OWNERS
- **Meetings:**
  - Regular AWS Subproject Meeting: [Fridays at 9:00 PT (Pacific Time)](https://docs.google.com/document/d/1FQx0BPlkkl1Bn0c9ocVBxYIKojpmrS1CFP5h0DI68AE/edit) (biweekly 2019 start date: Jan. 11th). [Convert to your timezone](http://www.thetimezoneconverter.com/?t=9:00&tz=PT%20%28Pacific%20Time%29).
    - [Meeting notes and Agenda](https://docs.google.com/document/d/1-i0xQidlXnFEP9fXHWkBxqySkXwJnrGJP9OGyP2_P14/edit).
    - [Meeting recordings](https://www.youtube.com/playlist?list=PL69nYSiGNLP29DzPOBBaJi-SO3AQ_b4HC).
### provider-azure
- **Owners:**
  - https://raw.githubusercontent.com/kubernetes-sigs/azuredisk-csi-driver/master/OWNERS
  - https://raw.githubusercontent.com/kubernetes-sigs/azurefile-csi-driver/master/OWNERS
  - https://raw.githubusercontent.com/kubernetes-sigs/cluster-api-provider-azure/master/OWNERS
  - https://raw.githubusercontent.com/kubernetes/cloud-provider-azure/master/OWNERS
- **Meetings:**
  - Regular Azure Subproject Meeting: [Wednesdays at 16:00 UTC](https://docs.google.com/document/d/1FQx0BPlkkl1Bn0c9ocVBxYIKojpmrS1CFP5h0DI68AE/edit) (biweekly). [Convert to your timezone](http://www.thetimezoneconverter.com/?t=16:00&tz=UTC).
    - [Meeting notes and Agenda](https://docs.google.com/document/d/1SpxvmOgHDhnA72Z0lbhBffrfe9inQxZkU9xqlafOW9k/edit).
    - [Meeting recordings](https://www.youtube.com/watch?v=yQLeUKi_dwg&list=PL69nYSiGNLP2JNdHwB8GxRs2mikK7zyc4).
### provider-gcp
- **Owners:**
  - https://raw.githubusercontent.com/kubernetes-sigs/gcp-compute-persistent-disk-csi-driver/master/OWNERS
  - https://raw.githubusercontent.com/kubernetes-sigs/gcp-filestore-csi-driver/master/OWNERS
  - https://raw.githubusercontent.com/kubernetes/cloud-provider-gcp/master/OWNERS
- **Meetings:**
  - Regular GCP Subproject Meeting: [Thursdays at 16:00 UTC](https://docs.google.com/document/d/1FQx0BPlkkl1Bn0c9ocVBxYIKojpmrS1CFP5h0DI68AE/edit) (biweekly). [Convert to your timezone](http://www.thetimezoneconverter.com/?t=16:00&tz=UTC).
    - [Meeting notes and Agenda](https://docs.google.com/document/d/1mtmwZ4oVSSWhbEw8Lfzvc7ig84qxUpdK6uHyJp8rSGU/edit).
### provider-ibmcloud
- **Owners:**
  - https://raw.githubusercontent.com/kubernetes-sigs/cluster-api-provider-ibmcloud/master/OWNERS
- **Meetings:**
  - Regular IBM Subproject Meeting: [Wednesdays at 14:00 EST](https://docs.google.com/document/d/1FQx0BPlkkl1Bn0c9ocVBxYIKojpmrS1CFP5h0DI68AE/edit) (biweekly). [Convert to your timezone](http://www.thetimezoneconverter.com/?t=14:00&tz=EST).
    - [Meeting notes and Agenda](https://docs.google.com/document/d/1qd_LTu5GFaxUhSWTHigowHt3XwjJVf1L57kupj8lnwg/edit).
### provider-openstack
- **Owners:**
  - https://raw.githubusercontent.com/kubernetes/cloud-provider-openstack/master/OWNERS
- **Meetings:**
  - Regular OpenStack Subproject Meeting: [Wednesdays at 08:00 PT (Pacific Time)](https://docs.google.com/document/d/1bW3j4hFN4D8rv2LFv-DybB3gcE5ISAaOO_OpvDCgrGg/edit) (biweekly starting Wednesday March 20, 2019). [Convert to your timezone](http://www.thetimezoneconverter.com/?t=08:00&tz=PT%20%28Pacific%20Time%29).
    - [Meeting notes and Agenda](https://docs.google.com/document/d/15UwgLbEyZyXXxVtsThcSuPiJru4CuqU9p3ttZSfTaY4/edit).
    - [Meeting recordings](https://www.youtube.com/watch?v=iCfUx7ilh0E&list=PL69nYSiGNLP20iTSChQ_i2QQmTBl3M7ax).
### provider-vsphere
- **Owners:**
  - https://raw.githubusercontent.com/kubernetes-sigs/vsphere-csi-driver/master/OWNERS
  - https://raw.githubusercontent.com/kubernetes/cloud-provider-vsphere/master/OWNERS
- **Meetings:**
  - Cloud Provider vSphere monthly syncup: [Wednesdays at 09:00 PT (Pacific Time)](https://docs.google.com/document/d/1FQx0BPlkkl1Bn0c9ocVBxYIKojpmrS1CFP5h0DI68AE/edit) (monthly - first Wednesday every month). [Convert to your timezone](http://www.thetimezoneconverter.com/?t=09:00&tz=PT%20%28Pacific%20Time%29).
    - [Meeting notes and Agenda](https://docs.google.com/document/d/1B0NmmKVh8Ea5hnNsbUsJC7ZyNCsq_6NXl5hRdcHlJgY/edit?usp=sharing).
    - [Meeting recordings](https://www.youtube.com/playlist?list=PLutJyDdkKQIpOT4bOfuO3MEMHvU1tRqyR).

[subproject-definition]: https://github.com/kubernetes/community/blob/master/governance.md#subprojects
<!-- BEGIN CUSTOM CONTENT -->

<!-- END CUSTOM CONTENT -->