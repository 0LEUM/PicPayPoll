## Steps to follow :scroll:

### 1. Fork it :

You can get your own fork/copy of [PicPayPoll](https://github.com/0LEUM/PicPayPoll) by using the <kbd><b>Fork</b></kbd></a> button.

### 2. Clone it :

You need to clone (download) it to local machine using

```sh
git clone https://github.com/0LEUM/PicPayPoll.git
```

> This makes a local copy of the repository in your machine.

### 3. Ready Steady Go... :

Once you have completed these steps, you are ready to start using the project.

### 4. Install all dependencies :

You have to install project dependencies for both Backend and Frontend

```sh
# It will install all Backend necessary dependencies
cd Backend
npm i

# It will install all Frontend necessary dependencies
cd user-frontend
npm i

# It will install all Frontend necessary dependencies
cd worker-frontend
npm i
```

**_Now comes adding some env files_**

```sh
# For "backend"
touch .env
- DATABASE_URL="your data base url"
- ACCESS_KEY_ID = "AWS User ACCESS_KEY"
- ACCESS_SECRET = "AWS User ACCESS_SECRET"
- RPC_URL = "your alchemy RPC_URL"

```

### 5. Now you are all set.. Start coding...
