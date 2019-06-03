# Changelog

## v0.7.0 (June 3, 2019)

### Changes
- Change default connection version to `v1` ([1a6eb4f](https://github.com/netology-group/svc-agent-rs/commit/1a6eb4f0adca9212daf29b7283cfb6267d7cffc6))



## v0.6.1 (May 18, 2019)

### Features
-  Add `properties` function to `OutgoingMessage` ([0a9d445](https://github.com/netology-group/svc-agent-rs/commit/0a9d445ba5eaadb740907583e5d5b35059ad3cd8))



## v0.6.0 (May 7, 2019)

### Changes
-  Use `QoS::AtMostOnce` for requests and `QoS::AtLeastOnce` for responses and events ([61834f0](https://github.com/netology-group/svc-agent-rs/commit/61834f0d7d41b882dd1ad1350c695a5b1ba7ad3e))



## v0.5.1 (Apr 24, 2019)

### Features
- Add `keep_alive_interval`, `reconnect_interval`, `outgoing_message_queue_size`, and `incomming_message_queue_size` configuration options ([3ba5a4d](https://github.com/netology-group/svc-agent-rs/commit/3ba5a4dfafbe7ae2326dfa7fda1b3a1802161c5c))

### Changes
- Make `clean_session` configuration option optional ([3ba5a4d](https://github.com/netology-group/svc-agent-rs/commit/3ba5a4dfafbe7ae2326dfa7fda1b3a1802161c5c))



## v0.5.0 (Apr 18, 2019)

### Features
- Add additional subscription functions ([3a2f2ab5](https://github.com/netology-group/svc-agent-rs/commit/3a2f2ab5e943519b5c9e4f6c7aaa2551c58d1fbb))

### Changes
- Replace `OutgoingResponseStatus` with `ResponseStatus` ([a6453f](https://github.com/netology-group/svc-agent-rs/commit/a6453f0222d95b23429d39a175d6d62190ee34ec))



## v0.4.1 (Apr 17, 2019)

### Features
- Implement `Dereserialize` for `OutgoingResponseStatus` ([296173b](https://github.com/netology-group/svc-agent-rs/commit/296173b815d4ecdaa1a3e83dc2e89704cd9d65cf))



## v0.4.0 (Apr 5, 2019)

### Features
- Add `Error` type ([f76c694](https://github.com/netology-group/svc-agent-rs/commit/f76c694b97ab3aeeac7186886a88720f58c34461))
- Implement `Clone` for `Agent` ([511d01c](https://github.com/netology-group/svc-agent-rs/commit/511d01c14e6d7ee839165e0cb4f7e74ad65f9f4c))



## v0.3.1 (Mar 5, 2019)

### Features
- Add `clean_session` configuration option ([5efa53c](https://github.com/netology-group/svc-agent-rs/commit/5efa53c65ab520c61352ed44122c5d7c6aa62a5b))



## v0.3.0 (Mar 1, 2019)

### Features
- Implement `Eq`, `Hash`, `Serialize` and `Deserialize` for `AgentId` and `SharedGroup` ([4a5fe76](https://github.com/netology-group/svc-agent-rs/commit/4a5fe76dbe8c269635998070a7c742aa41595570))
- Add `Service` connection mode

### Changes
- Replace `Agent` connection mode with `Default`



## v0.2.0 (Feb 14, 2019)

### Features
- Add `Addressable` trait ([39d5faa](https://github.com/netology-group/svc-agent-rs/commit/39d5faad19f6209b88beface622c273e90dcd9c7))

### Changes
- Change arguments of `OutgoingRequestProperties` constructor ([cba56a9](https://github.com/netology-group/svc-agent-rs/commit/cba56a98f172a111042db9e544f8bd6762217f3e))
- Replace `agent_id` with `as_agent_id` ([39d5faa](https://github.com/netology-group/svc-agent-rs/commit/39d5faad19f6209b88beface622c273e90dcd9c7))



## v0.1.0 (Feb 12, 2019)

Initial release