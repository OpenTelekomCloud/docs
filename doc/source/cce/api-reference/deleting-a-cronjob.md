# Deleting a CronJob<a name="cce_02_0226"></a>

## Function<a name="section41928453"></a>

This API is used to delete a CronJob.

## URI<a name="section41811761"></a>

DELETE /apis/batch/v1beta1/namespaces/\{namespace\}/cronjobs/\{name\}

[Table 1](#d0e40914)  describes the parameters of this API.

**Table  1**  Description

<a name="d0e40914"></a>
<table><thead align="left"><tr id="row55265855"><th class="cellrowborder" valign="top" width="33%" id="mcps1.2.4.1.1"><p id="p65652297517"><a name="p65652297517"></a><a name="p65652297517"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="23%" id="mcps1.2.4.1.2"><p id="p165661629135114"><a name="p165661629135114"></a><a name="p165661629135114"></a>Mandatory</p>
</th>
<th class="cellrowborder" valign="top" width="44%" id="mcps1.2.4.1.3"><p id="p14567629115114"><a name="p14567629115114"></a><a name="p14567629115114"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row64362693"><td class="cellrowborder" valign="top" width="33%" headers="mcps1.2.4.1.1 "><p id="p45995684"><a name="p45995684"></a><a name="p45995684"></a>pretty</p>
</td>
<td class="cellrowborder" valign="top" width="23%" headers="mcps1.2.4.1.2 "><p id="p34662956"><a name="p34662956"></a><a name="p34662956"></a>No</p>
</td>
<td class="cellrowborder" valign="top" width="44%" headers="mcps1.2.4.1.3 "><p id="p56236036"><a name="p56236036"></a><a name="p56236036"></a>If 'true', then the output is pretty printed.</p>
</td>
</tr>
<tr id="row36362277"><td class="cellrowborder" valign="top" width="33%" headers="mcps1.2.4.1.1 "><p id="p59663353"><a name="p59663353"></a><a name="p59663353"></a>name</p>
</td>
<td class="cellrowborder" valign="top" width="23%" headers="mcps1.2.4.1.2 "><p id="p893425"><a name="p893425"></a><a name="p893425"></a>Yes</p>
</td>
<td class="cellrowborder" valign="top" width="44%" headers="mcps1.2.4.1.3 "><p id="p5258614"><a name="p5258614"></a><a name="p5258614"></a>name of the CronJob</p>
</td>
</tr>
<tr id="row47327528"><td class="cellrowborder" valign="top" width="33%" headers="mcps1.2.4.1.1 "><p id="p8324587"><a name="p8324587"></a><a name="p8324587"></a>namespace</p>
</td>
<td class="cellrowborder" valign="top" width="23%" headers="mcps1.2.4.1.2 "><p id="p3202926"><a name="p3202926"></a><a name="p3202926"></a>Yes</p>
</td>
<td class="cellrowborder" valign="top" width="44%" headers="mcps1.2.4.1.3 "><p id="p58110425"><a name="p58110425"></a><a name="p58110425"></a>object name and auth scope, such as for teams and projects</p>
</td>
</tr>
<tr id="row53231781"><td class="cellrowborder" valign="top" width="33%" headers="mcps1.2.4.1.1 "><p id="p16807041"><a name="p16807041"></a><a name="p16807041"></a>gracePeriodSeconds</p>
</td>
<td class="cellrowborder" valign="top" width="23%" headers="mcps1.2.4.1.2 "><p id="p19193048"><a name="p19193048"></a><a name="p19193048"></a>No</p>
</td>
<td class="cellrowborder" valign="top" width="44%" headers="mcps1.2.4.1.3 "><p id="p11133076"><a name="p11133076"></a><a name="p11133076"></a>The duration in seconds before the object should be deleted. Value must be a non-negative integer. The value zero indicates delete immediately. If this value is nil, the default grace period for the specified type will be used. Defaults to a per object value if not specified. Zero means immediate deletion.</p>
</td>
</tr>
<tr id="row33088828"><td class="cellrowborder" valign="top" width="33%" headers="mcps1.2.4.1.1 "><p id="p62949386"><a name="p62949386"></a><a name="p62949386"></a>orphanDependents</p>
</td>
<td class="cellrowborder" valign="top" width="23%" headers="mcps1.2.4.1.2 "><p id="p65735472"><a name="p65735472"></a><a name="p65735472"></a>No</p>
</td>
<td class="cellrowborder" valign="top" width="44%" headers="mcps1.2.4.1.3 "><p id="p22973015"><a name="p22973015"></a><a name="p22973015"></a>Deprecated: Use the PropagationPolicy. This field will be deprecated in 1.7. Should the dependent objects be orphaned. If true/false, the "orphan" finalizer will be added to/removed from the object's finalizers list. Either this field or PropagationPolicy may be set, but not both.</p>
</td>
</tr>
<tr id="row5430546"><td class="cellrowborder" valign="top" width="33%" headers="mcps1.2.4.1.1 "><p id="p37221085"><a name="p37221085"></a><a name="p37221085"></a>propagationPolicy</p>
</td>
<td class="cellrowborder" valign="top" width="23%" headers="mcps1.2.4.1.2 "><p id="p62117884"><a name="p62117884"></a><a name="p62117884"></a>No</p>
</td>
<td class="cellrowborder" valign="top" width="44%" headers="mcps1.2.4.1.3 "><p id="p1830145261812"><a name="p1830145261812"></a><a name="p1830145261812"></a>Whether and how garbage collection will be performed. Either this field or OrphanDependents may be set, but not both. The default policy is decided by the existing finalizer set in the metadata.finalizers and the resource-specific default policy. Acceptable values are: 'Orphan' - orphan the dependents; 'Background' - allow the garbage collector to delete the dependents in the background; 'Foreground' - a cascading policy that deletes all dependents in the foreground.</p>
</td>
</tr>
</tbody>
</table>

## Request<a name="section40761536"></a>

**Request parameters:**

For the description about request parameters, see  [Table 2](deleting-a-job.md#d0e41006).

**Example request:**

-   Deleting only the CronJob \(the Job and pod are not deleted\):

    ```
    {
        "kind": "DeleteOptions",
        "apiVersion": "v1",
        "gracePeriodSeconds": 0,
        "propagationPolicy": "Orphan"
    }
    ```

-   Deleting the pod, Job, and then the CronJob:

    ```
    {
        "kind": "DeleteOptions",
        "apiVersion": "v1",
        "propagationPolicy": "Foreground"
    }
    ```

-   Deleting the CronJob, Job, and then the pod:

    ```
    {
        "kind": "DeleteOptions",
        "apiVersion": "v1",
        "propagationPolicy": "Background"
    }
    ```


## Response<a name="section31309505"></a>

**Response parameters:**

For the description about response parameters, see  [Table 2](deleting-a-secret.md#table13766144711235).

**Example response:**

```
{
  "kind": "CronJob",
  "apiVersion": "batch/v1beta1",
  "metadata": {
    "name": "cronjob-test",
    "namespace": "default",
    "selfLink": "/apis/batch/v1beta1/namespaces/default/cronjobs/cronjob-test",
    "uid": "4d78b666-2200-11e8-96aa-fa163ecd089c",
    "resourceVersion": "441442",
    "creationTimestamp": "2018-03-07T12:08:52Z",
    "deletionTimestamp": "2018-03-07T12:15:11Z",
    "deletionGracePeriodSeconds": 0,
    "annotations": {
      "container.io/container-0": "172.16.5.235:20202/test/nginx.png",
      "description": ""
    },
    "finalizers": [
      "orphan"
    ],
    "enable": true
  },
  "spec": {
    "schedule": "*/59 * * * *",
    "concurrencyPolicy": "Allow",
    "suspend": false,
    "jobTemplate": {
      "metadata": {
        "creationTimestamp": null,
        "enable": true
      },
      "spec": {
        "template": {
          "metadata": {
            "creationTimestamp": null,
            "labels": {
              "sjname": "cronjob-test"
            },
            "enable": true
          },
          "spec": {
            "containers": [
              {
                "name": "container-0",
                "image": "nginx:stable-perl",
                "resources": {

                },
                "lifecycle": {

                },
                "terminationMessagePath": "/dev/termination-log",
                "terminationMessagePolicy": "File",
                "imagePullPolicy": "IfNotPresent"
              }
            ],
            "restartPolicy": "OnFailure",
            "terminationGracePeriodSeconds": 30,
            "dnsPolicy": "ClusterFirst",
            "securityContext": {

            },
            "imagePullSecrets": [
              {
                "name": "default-secret"
              }
            ],
            "schedulerName": "default-scheduler"
          }
        }
      }
    },
    "successfulJobsHistoryLimit": 3,
    "failedJobsHistoryLimit": 1
  },
  "status": {

  }
}
```

## Status Code<a name="section13350095"></a>

[Table 2](#d0e41189)  describes the status code of this API.

**Table  2**  Status code

<a name="d0e41189"></a>
<table><thead align="left"><tr id="row46934970"><th class="cellrowborder" valign="top" width="50%" id="mcps1.2.3.1.1"><p id="p43636236"><a name="p43636236"></a><a name="p43636236"></a>Status Code</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.2.3.1.2"><p id="p44874251"><a name="p44874251"></a><a name="p44874251"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row10935710"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.2.3.1.1 "><p id="p13377326"><a name="p13377326"></a><a name="p13377326"></a>200</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.2.3.1.2 "><p id="p9821602"><a name="p9821602"></a><a name="p9821602"></a>Delete a Job resource object successfully.</p>
</td>
</tr>
</tbody>
</table>

For the description about error status codes, see  [Status Code](status-code.md).

