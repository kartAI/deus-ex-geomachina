### SQL commands for user mgmt
Change password for user
```sql
ALTER USER kartai_ro_yy WITH PASSWORD 'password-can-be-passphrase';
```

```sql
-- Steg 1: Opprett den nye brukeren med en passord
CREATE USER kartai_ro_yy WITH PASSWORD 'password-can-be-passphrase';

-- Steg 2: Gi den nye brukeren de samme rettighetene som den eksisterende brukeren
GRANT kartai_ro TO kartai_ro_yy;
```