# Make crAPI work

Derivative of https://github.com/OWASP/crAPI/tree/v1.1.5

Uses containers rebuilt from a mix of RC 1.1.6 and 1.1.5 containers but pushed onto a different dockerhub part as official crapi currently does not properly have tags present (or in a working state).

Setup should work out of the box. (`docker compose up -d`)
Listens on
http://localhost:8888/ (crAPI ui)
http://localhost:8025/ (Mailhog)
