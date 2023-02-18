# WordPress Docker Setup

## Usage
```bash
sh ./start.sh
```

### To Do:
- Add `/etc/hosts` checks to see if site added to `/docker/.env` already exists.
- Add way for `/etc/hosts` to be updated if previous condition is `false`.
- Add dns masking so multiple container groups can run at the same time.
