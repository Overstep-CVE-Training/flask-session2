# Changelog

## Version 0.1

First public preview release.

## Version 0.1.1

Fixed MongoDB backend InvalidDocument Error.

## Version 0.2

- Added `SqlAlchemySessionInterface`.
- Added support for cookie session id signing.
- Various bugfixes.

## Version 0.2.1

Fixed signing failure.

## Version 0.2.2

Added support for non-permanent session.

## Version 0.2.3

- Fixed signing failure in Python 3.x
- Fixed MongoDBSessionInterface failure in Python 3.x
- Fixed SqlAlchemySessionInterface failure in Python 3.x
- Fixed StrictRedis support

## Version 0.3

- SqlAlchemySessionInterface is using LargeBinary type to store data now
- Fixed MongoDBSessionInterface delete method not found
- Fixed TypeError when getting store_id using a signer

## Version 0.3.1

- SqlAlchemySessionInterface is using VARCHAR(255) to store session id now
- SqlAlchemySessionInterface won't run `db.create_all` anymore

## Version 0.3.2

- Changed `werkzeug.contrib.cache` to `cachelib`

## Version 0.4.0

- Added support for `SESSION_COOKIE_SAMESITE`
