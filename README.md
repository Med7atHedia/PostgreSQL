
## 1. install postgresql

```bash
sudo apt install postgresql
```

## 2. version

```bash
psql --version
```

## 3. open postgresql

```bash
sudo su postgres
```

# Using PSQL

sudo -u postgres psql

# List All Users in PostgreSQL

sudo -u postgres psql
\du

# create user

createuser --createdb --username postgres --no-createrole --no-superuser --pwprompt odoo16

# Listing Databases

\l



# Set root user credentials

sudo -u postgres psql
ALTER USER postgres PASSWORD 'newpassword';
psql -U postgres -h localhost

# Solution status

pg_lsclusters
