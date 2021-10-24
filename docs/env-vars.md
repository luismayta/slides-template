<!-- Space: SlidesTemplate -->
<!-- Parent: Project -->
<!-- Title: Env Vars -->

<!-- Label: SlidesTemplate -->
<!-- Label: Project -->
<!-- Label: Env Vars -->
<!-- Include: docs/disclaimer.md -->
<!-- Include: ac:toc -->

---

## Env Vars

### Application

Following a list of available dynamic ENV vars:

**database** (All vars for database)

- `DATABASE_URL`: url connection database.

**celery** (All vars for taskmanager)

- `CELERY_TASK_ALWAYS_EAGER`: ?.
- `CELERY_BROKER_URL`: celery broker save messages.
- `CELERY_RESULT_BACKEND`: backend save result.

**front** (all vars for front)

- `FRONT_URL`: url front of yax.

**redis** (all vars for redis)

- `REDIS_HOST`: host of redis.
- `REDIS_PORT`: port of redis.
- `REDIS_DB`: db number for save information.

### socket (rfid-socket)

**socket.io** (all vars for socket.io)

- `REDIS_SOCKET_IO_HOST`: url redis socket io host.
- `REDIS_SOCKET_IO_PORT`: url redis socket io port.

### devices (rfid-devices)

**devices** (all vars for devices)

- `YAX_DEV_RES_HOST`: ?.
- `YAX_DEV_RES_PORT`: ?.
- `YAX_DEV_PUB_HOST`: ?.
- `YAX_DEV_PUB_PORT`: ?.
- `YAX_DEVICE_URL`: Api of service rfid-devices

### sync (?)

**sync** (all vars for sync)

- `SYNC_ENABLED`: ?.
- `SYNC_HOST`: ?.
- `SYNC_PORT`: ?.
- `SYNC_USERNAME`: ?.
- `SYNC_PASSWORD`: Api of service rfid-devices

### blockchain (?)

**blockchain** (all vars for blockchain)

- `YAX_BLOCKCHAIN_URL`: url of service blockchain.
- `YAX_BLOCKCHAIN_ENABLED`: ?.
