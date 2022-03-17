# Vintrace Coding Challenge
## Joshua Sommerfeld

I've split this project into a `server` and `front-end` folder, with each having it's own specific README and git sub-repo.

## Quick Start
As long as you have the following installed, you're good to go:
- Java 11
- node 16
- yarn

You can do that at all together with the following:
```bash
	cd vintrace-coding-challenge-front-end
	yarn startAll
```

OR

You can start the services individually like so:
```bash
	cd vintrace-coding-challenge-server
	./gradlew bootRun
```
Then opening another CLI session and running
```bash
	cd vintrace-coding-challenge-front-end
	yarn start
```

