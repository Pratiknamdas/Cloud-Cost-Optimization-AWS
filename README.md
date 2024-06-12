# Cloud-Cost-Optimization-AWS-

Implemented a Lambda Function That identifies and delete the stale EBS snapshots to save on storage cost. And lambda function also retrieves list of active instances. It checks if each snapshot's associated volume is connected to any active instance. If not, the function deletes the snapshot, thus optimizing storage costs by removing unnecessary data.
