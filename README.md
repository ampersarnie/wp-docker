# WordPress Docker Setup
Simple docker setup for working with WordPress enviroments.

## Usage
Create a `.env` file in the root of your project.

```bash
bash docker/start
```

### To Do:
- Add `/etc/hosts` checks to see if site added to `.env.docker` already exists.
- Add way for `/etc/hosts` to be updated if previous condition is `false`.
- Add dns masking so multiple container groups can run at the same time.
- Add check for WordPress VIP and to implement `mu-plugins` and `client-mu-plugins` dirs.
