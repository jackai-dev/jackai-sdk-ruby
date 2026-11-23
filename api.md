# JackAI Platform OS Hub API (public subset) Ruby API

<!-- omniwrap-api-reference eyJjb250cmFjdF9maW5nZXJwcmludCI6ImM3Y2E1ZTVlYmI0YzA5MjkxMGVjNzJiMzcxZTE4ODMwMzM1OGM1ZTM0ZDI5MDhjMGE4OGY3ODJhMjQxMTYyY2YiLCJvcGVyYXRpb25fY291bnQiOjgsInJlbmRlcmVyIjoicnVieSIsInZlcnNpb24iOiIxLjUuMCJ9 -->

This generated index is tied to Semantic IR `1.14.0` and contract fingerprint `c7ca5e5ebb4c092910ec72b371e188303358c5e34d2908c0a88f782a241162cf`. Every operation below is rendered from the same semantic contract and artifact-attested public member allocation as the SDK.

SDK maturity: **experimental**  
Artifact evidence: [`omniwrap-artifact.json`](omniwrap-artifact.json) binds this file by SHA-256 and is revalidated by the package gate.

## Resource `health`

<!-- omniwrap-api-operation eyJleGFtcGxlX3JlYXNvbiI6Imxhbmd1YWdlLWV4YW1wbGUtbm90LWdlbmVyYXRlZCIsImV4YW1wbGVfc3RhdHVzIjoidW5zdXBwb3J0ZWQiLCJtZW1iZXIiOiJnZXRfaGVhbHRoIiwibWV0aG9kIjoiR0VUIiwib3BlcmF0aW9uX2lkIjoiZ2V0SGVhbHRoIiwicGF0aCI6Ii9oZWFsdGgiLCJyZXNvdXJjZSI6ImhlYWx0aCIsInNlY3Rpb25fc2hhMjU2IjoiOTUzN2JjZjM5MTQ0OWVkYjJmNzc1N2NmOTIzNmI3YmJmMzk1NTNjOTljOTRhMTgwNTcyZTg4OGVmNzFmZTcyNSIsInNpZ25hdHVyZV9zaGEyNTYiOiIwMTVmZDY2MTBiYmU3OTRlYTUyZTNkNjZmMzZhODBjNWNlZTUxODlmOWE1NjU5OWRmYTUyNmM0Mjg0NTE3NjMxIn0 -->
### `client.get_health`

Operation ID: `getHealth`  
Route: `GET` `/health`  

#### Signature

```ruby
def get_health()
```

#### Parameters

| Name | In | Required | Contract type | Description |
| --- | --- | --- | --- | --- |
| _none_ | | | | |

#### Responses

| Status | Description | Content |
| --- | --- | --- |
| `200` | Hub liveness status | none |

#### Canonical required-input example

```json
{
  "parameters": []
}
```

#### SDK call example

Example status: `unsupported`  
Unsupported reason: `language-example-not-generated`

<!-- omniwrap-api-operation-end eyJvcGVyYXRpb25faWQiOiJnZXRIZWFsdGgifQ -->

## Resource `kernel`

<!-- omniwrap-api-operation eyJleGFtcGxlX3JlYXNvbiI6Imxhbmd1YWdlLWV4YW1wbGUtbm90LWdlbmVyYXRlZCIsImV4YW1wbGVfc3RhdHVzIjoidW5zdXBwb3J0ZWQiLCJtZW1iZXIiOiJmYWlsX3VzYWdlX3F1b3RhIiwibWV0aG9kIjoiUE9TVCIsIm9wZXJhdGlvbl9pZCI6ImZhaWxVc2FnZVF1b3RhIiwicGF0aCI6Ii92MS9rZXJuZWwvdXNhZ2UvZmFpbCIsInJlc291cmNlIjoia2VybmVsIiwic2VjdGlvbl9zaGEyNTYiOiIxMWRlYmY0ZTg4NWE2YzcwODRjYWU1NGQyNzYyZjViMjgxMWE3ZmU2MTBkNGNmN2JjMGNmNWM2ZTdjZjRlMTk0Iiwic2lnbmF0dXJlX3NoYTI1NiI6ImJkZGNjOWIzODYyZDljYTJjMDc4MzIxZGE0NGUyYjJmZjUzN2VhOGM0MzUwYzcxM2MxN2I5YzFhNDUzNmFhYjUifQ -->
### `client.fail_usage_quota`

Operation ID: `failUsageQuota`  
Route: `POST` `/v1/kernel/usage/fail`  

#### Signature

```ruby
def fail_usage_quota()
```

#### Parameters

| Name | In | Required | Contract type | Description |
| --- | --- | --- | --- | --- |
| _none_ | | | | |

#### Responses

| Status | Description | Content |
| --- | --- | --- |
| `200` | Reservation released | none |

#### Canonical required-input example

```json
{
  "parameters": []
}
```

#### SDK call example

Example status: `unsupported`  
Unsupported reason: `language-example-not-generated`

<!-- omniwrap-api-operation-end eyJvcGVyYXRpb25faWQiOiJmYWlsVXNhZ2VRdW90YSJ9 -->

<!-- omniwrap-api-operation eyJleGFtcGxlX3JlYXNvbiI6Imxhbmd1YWdlLWV4YW1wbGUtbm90LWdlbmVyYXRlZCIsImV4YW1wbGVfc3RhdHVzIjoidW5zdXBwb3J0ZWQiLCJtZW1iZXIiOiJmaW5hbGl6ZV91c2FnZV9xdW90YSIsIm1ldGhvZCI6IlBPU1QiLCJvcGVyYXRpb25faWQiOiJmaW5hbGl6ZVVzYWdlUXVvdGEiLCJwYXRoIjoiL3YxL2tlcm5lbC91c2FnZS9maW5hbGl6ZSIsInJlc291cmNlIjoia2VybmVsIiwic2VjdGlvbl9zaGEyNTYiOiI1MDc1OWMzNzI5MDI0NDU3NjM5ZDk4MzNlNTEwYjI1ZTQ4ZDQ0YTg2OWQ2M2YxMWM3YTE0MjI4MjljYzk2N2Q4Iiwic2lnbmF0dXJlX3NoYTI1NiI6IjkxYTQ4ZmU5MTU5NDM5OGU0YWU0NTFiMDZjYTk3N2Q3NGJjZWYzZTI3Y2ZhNWI3NjgxYjYwZjhkMjA4NDdhYTcifQ -->
### `client.finalize_usage_quota`

Operation ID: `finalizeUsageQuota`  
Route: `POST` `/v1/kernel/usage/finalize`  

#### Signature

```ruby
def finalize_usage_quota()
```

#### Parameters

| Name | In | Required | Contract type | Description |
| --- | --- | --- | --- | --- |
| _none_ | | | | |

#### Responses

| Status | Description | Content |
| --- | --- | --- |
| `200` | Reservation finalized | none |

#### Canonical required-input example

```json
{
  "parameters": []
}
```

#### SDK call example

Example status: `unsupported`  
Unsupported reason: `language-example-not-generated`

<!-- omniwrap-api-operation-end eyJvcGVyYXRpb25faWQiOiJmaW5hbGl6ZVVzYWdlUXVvdGEifQ -->

<!-- omniwrap-api-operation eyJleGFtcGxlX3JlYXNvbiI6Imxhbmd1YWdlLWV4YW1wbGUtbm90LWdlbmVyYXRlZCIsImV4YW1wbGVfc3RhdHVzIjoidW5zdXBwb3J0ZWQiLCJtZW1iZXIiOiJyZXNlcnZlX3VzYWdlX3F1b3RhIiwibWV0aG9kIjoiUE9TVCIsIm9wZXJhdGlvbl9pZCI6InJlc2VydmVVc2FnZVF1b3RhIiwicGF0aCI6Ii92MS9rZXJuZWwvdXNhZ2UvcmVzZXJ2ZSIsInJlc291cmNlIjoia2VybmVsIiwic2VjdGlvbl9zaGEyNTYiOiI3NjNhM2ZjNDliN2VkNGNkZDRmN2Y0ZTZkOGQ4YmUwYWNiZTNkNDBiNWQ5ZmI1MGJjZTllMmM1MWQwMWRmMzZlIiwic2lnbmF0dXJlX3NoYTI1NiI6IjYxMTExZjA2N2I4NzgxMTBjZjI1MjM3M2ZhOTVjODdkNmY0MjY2YjU5NWVlYTM1MDcwNmJhZjA0Mzc1MzcyMjYifQ -->
### `client.reserve_usage_quota`

Operation ID: `reserveUsageQuota`  
Route: `POST` `/v1/kernel/usage/reserve`  

#### Signature

```ruby
def reserve_usage_quota()
```

#### Parameters

| Name | In | Required | Contract type | Description |
| --- | --- | --- | --- | --- |
| _none_ | | | | |

#### Responses

| Status | Description | Content |
| --- | --- | --- |
| `200` | Reservation lease created | none |

#### Canonical required-input example

```json
{
  "parameters": []
}
```

#### SDK call example

Example status: `unsupported`  
Unsupported reason: `language-example-not-generated`

<!-- omniwrap-api-operation-end eyJvcGVyYXRpb25faWQiOiJyZXNlcnZlVXNhZ2VRdW90YSJ9 -->

## Resource `user`

<!-- omniwrap-api-operation eyJleGFtcGxlX3JlYXNvbiI6Imxhbmd1YWdlLWV4YW1wbGUtbm90LWdlbmVyYXRlZCIsImV4YW1wbGVfc3RhdHVzIjoidW5zdXBwb3J0ZWQiLCJtZW1iZXIiOiJnZXRfY3VycmVudF91c2VyIiwibWV0aG9kIjoiR0VUIiwib3BlcmF0aW9uX2lkIjoiZ2V0Q3VycmVudFVzZXIiLCJwYXRoIjoiL3VzZXIvbWUiLCJyZXNvdXJjZSI6InVzZXIiLCJzZWN0aW9uX3NoYTI1NiI6Ijc1NDk2YzJkYWJkYmE0MzQyZjMxNGRiODc1YTc4MGEyYjEzNjBlZGZhODU0OTZhM2JmZTU2NTY5ZDdjZjVlZDYiLCJzaWduYXR1cmVfc2hhMjU2IjoiMGJjZDRmYmVhZmM4Y2Y5YWYwODEzZTAyN2NkMWE3NDZkYjRiNDVjZWQ4OWY1MGVlNzY0YTlkMTU0YTIxNjVjOSJ9 -->
### `client.get_current_user`

Operation ID: `getCurrentUser`  
Route: `GET` `/user/me`  

#### Signature

```ruby
def get_current_user()
```

#### Parameters

| Name | In | Required | Contract type | Description |
| --- | --- | --- | --- | --- |
| _none_ | | | | |

#### Responses

| Status | Description | Content |
| --- | --- | --- |
| `200` | Current user context | none |

#### Canonical required-input example

```json
{
  "parameters": []
}
```

#### SDK call example

Example status: `unsupported`  
Unsupported reason: `language-example-not-generated`

<!-- omniwrap-api-operation-end eyJvcGVyYXRpb25faWQiOiJnZXRDdXJyZW50VXNlciJ9 -->

<!-- omniwrap-api-operation eyJleGFtcGxlX3JlYXNvbiI6Imxhbmd1YWdlLWV4YW1wbGUtbm90LWdlbmVyYXRlZCIsImV4YW1wbGVfc3RhdHVzIjoidW5zdXBwb3J0ZWQiLCJtZW1iZXIiOiJnZXRfc2lnbnVwX3BvbGljeSIsIm1ldGhvZCI6IkdFVCIsIm9wZXJhdGlvbl9pZCI6ImdldFNpZ251cFBvbGljeSIsInBhdGgiOiIvdXNlci9hdXRoL3NpZ251cC1wb2xpY3kiLCJyZXNvdXJjZSI6InVzZXIiLCJzZWN0aW9uX3NoYTI1NiI6ImEzNTBmNjk2ZDc2MmUwNWI3YTc0ZWJjODI4NGJmYWU4ZWU5NzhiZTllOTllMjYwMzY5Nzg5YmVkYTUzY2VlOTMiLCJzaWduYXR1cmVfc2hhMjU2IjoiY2JlZWQ0ZjI2NGU0MDNmYThkNTBjMTVkOTRkNzUxYTMxNmE0NzMxOWY2ZDM4M2ZjMDRjZWI1MTcyYmQ2MDBkZSJ9 -->
### `client.get_signup_policy`

Operation ID: `getSignupPolicy`  
Route: `GET` `/user/auth/signup-policy`  

#### Signature

```ruby
def get_signup_policy()
```

#### Parameters

| Name | In | Required | Contract type | Description |
| --- | --- | --- | --- | --- |
| _none_ | | | | |

#### Responses

| Status | Description | Content |
| --- | --- | --- |
| `200` | Current signup policy | none |

#### Canonical required-input example

```json
{
  "parameters": []
}
```

#### SDK call example

Example status: `unsupported`  
Unsupported reason: `language-example-not-generated`

<!-- omniwrap-api-operation-end eyJvcGVyYXRpb25faWQiOiJnZXRTaWdudXBQb2xpY3kifQ -->

<!-- omniwrap-api-operation eyJleGFtcGxlX3JlYXNvbiI6Imxhbmd1YWdlLWV4YW1wbGUtbm90LWdlbmVyYXRlZCIsImV4YW1wbGVfc3RhdHVzIjoidW5zdXBwb3J0ZWQiLCJtZW1iZXIiOiJsb2dpbl91c2VyIiwibWV0aG9kIjoiUE9TVCIsIm9wZXJhdGlvbl9pZCI6ImxvZ2luVXNlciIsInBhdGgiOiIvdXNlci9hdXRoL2xvZ2luIiwicmVzb3VyY2UiOiJ1c2VyIiwic2VjdGlvbl9zaGEyNTYiOiIzMzU0M2ZhM2JiMDA1ODc5ZWRkMGQzMzY3ODA1Mjg1MjRhNGNmMmU4NDJjZmNjMTFlNzgyYjMzZmMzNjgzOTZhIiwic2lnbmF0dXJlX3NoYTI1NiI6IjVkZDhmNzQzODRlNzIzNzI4ZWI4NzQxNjU0NzQ3ZjkzMjYyMTc2NjhkOGQzMjFkN2VkMjAxY2Y2NDVlOWZkNDQifQ -->
### `client.login_user`

Operation ID: `loginUser`  
Route: `POST` `/user/auth/login`  

#### Signature

```ruby
def login_user()
```

#### Parameters

| Name | In | Required | Contract type | Description |
| --- | --- | --- | --- | --- |
| _none_ | | | | |

#### Responses

| Status | Description | Content |
| --- | --- | --- |
| `200` | Authenticated session or MFA challenge | none |

#### Canonical required-input example

```json
{
  "parameters": []
}
```

#### SDK call example

Example status: `unsupported`  
Unsupported reason: `language-example-not-generated`

<!-- omniwrap-api-operation-end eyJvcGVyYXRpb25faWQiOiJsb2dpblVzZXIifQ -->

<!-- omniwrap-api-operation eyJleGFtcGxlX3JlYXNvbiI6Imxhbmd1YWdlLWV4YW1wbGUtbm90LWdlbmVyYXRlZCIsImV4YW1wbGVfc3RhdHVzIjoidW5zdXBwb3J0ZWQiLCJtZW1iZXIiOiJzdWJtaXRfd2FpdGxpc3RfcmVxdWVzdCIsIm1ldGhvZCI6IlBPU1QiLCJvcGVyYXRpb25faWQiOiJzdWJtaXRXYWl0bGlzdFJlcXVlc3QiLCJwYXRoIjoiL3VzZXIvYXV0aC93YWl0bGlzdCIsInJlc291cmNlIjoidXNlciIsInNlY3Rpb25fc2hhMjU2IjoiMzJhYTcxNjE2OGQ0ZTBiOTQ3NTI1YTAxNmY3Y2M2MmEwY2ExNmM3MzcyYzhmZmM3ZDc1NzVlNWUyNjIwZGFmMiIsInNpZ25hdHVyZV9zaGEyNTYiOiJkNmYyYmJmYjg2NzBhNDYzNWE4MzE0NjNlZWU4MzQ2NDg0NmM3OTQ3MTU4ZWY2NTBlYmY2Mzc0MWRiNjE5Zjc2In0 -->
### `client.submit_waitlist_request`

Operation ID: `submitWaitlistRequest`  
Route: `POST` `/user/auth/waitlist`  

#### Signature

```ruby
def submit_waitlist_request()
```

#### Parameters

| Name | In | Required | Contract type | Description |
| --- | --- | --- | --- | --- |
| _none_ | | | | |

#### Responses

| Status | Description | Content |
| --- | --- | --- |
| `202` | Waitlist request recorded with an opaque WL- reference | none |

#### Canonical required-input example

```json
{
  "parameters": []
}
```

#### SDK call example

Example status: `unsupported`  
Unsupported reason: `language-example-not-generated`

<!-- omniwrap-api-operation-end eyJvcGVyYXRpb25faWQiOiJzdWJtaXRXYWl0bGlzdFJlcXVlc3QifQ -->

