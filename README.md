# LoadTesting
Brain dump - Keep it clean, no specifics...

## Getting started
- [ ] 10K foot view
- [ ] Tooling option list
- [ ] Issues & challenges
- [ ] Tasks

## 10K Foot View
...

## Tooling Option List
### Locus.io
[Locus](https://docs.locust.io/en/latest/quickstart.html) an interesting looking tool:
* Tests as code (python)
* Custom client by extending Locust & firing necessary events
* Can scale-out for large scale simulation
* Open source
* Authors claim to be built in response to frustrations with JMeter & TSsung

## Issues & Challenges
* Some journies are intamately linked to client side security implementation.
* Access to e2e test environment with sufficient scale
** Test in dev
*** Use stubs with sleeps consistent with performance of back-end (measured under no load on)
*** Possibly sufficient for low user counts for now

** Pre-Prod
*** Target deployment dates?
*** Capacity capabilities on backend?

## Tasks

### Generic Items
- [ ] Entitlements to load test, time limited & dynamically enabled
- [ ] OAM module for test client SSO token 
