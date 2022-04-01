# Waiters

> [Index](../README.md) > [signer](./README.md) > Waiters

!!! note ""

    Auto-generated documentation for [signer](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/signer.html#signer)
    type annotations stubs module [types-aiobotocore-signer](https://pypi.org/project/types-aiobotocore-signer/).

## SuccessfulSigningJobWaiter

Type annotations and code completion for `#!python session.create_client("signer").get_waiter("successful_signing_job")`.
[:material-aws: boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/signer.html#signer.Waiter.SuccessfulSigningJob)

```python title="Usage example"
from aiobotocore.session import Session

from types_aiobotocore_signer.waiter import SuccessfulSigningJobWaiter

def get_successful_signing_job_waiter() -> SuccessfulSigningJobWaiter:
    return Session().client("signer").get_waiter("successful_signing_job")
```


### wait

Type annotations and code completion for `#!python SuccessfulSigningJobWaiter.wait` method.

```python title="Method definition"
await def wait(
    self,
    *,
    jobId: str,
    WaiterConfig: WaiterConfigTypeDef = ...,  # (1)
) -> None:
    ...
```

1. See [:material-code-braces: WaiterConfigTypeDef](./type_defs.md#waiterconfigtypedef) 


```python title="Usage example with kwargs"
kwargs: DescribeSigningJobRequestSuccessfulSigningJobWaitTypeDef = {  # (1)
    "jobId": ...,
}

parent.wait(**kwargs)
```

1. See [:material-code-braces: DescribeSigningJobRequestSuccessfulSigningJobWaitTypeDef](./type_defs.md#describesigningjobrequestsuccessfulsigningjobwaittypedef) 
