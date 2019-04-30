# opat-db
opat-db initializes and updates the backend database flow to support opat


## Databases

### Raw

This database contains all the raw download files. The purpose is to make comparison between new and old download fast. It is not supposed to be queried directly. All queries should go through the securities masters table.
