#Rian Oshwald Selorio

I am going to finish BSCpE on time!

**Steps**
1. Make the project as local repo

```bash
git init
git config --global user.name "username"
git config --global user.email "email"
```

## Prepare changes to be saved locally
```bash
git add .
```

## Commit change / Make changes final a make a save point
```bash
git commit -m "Description"
```

## Rename Branch `master` to `main`
```bash
git branch -M main
```

# 2. Create a remote repo in Github

# 3. Connect both repo so they

## Link local repo to remote repo

```bash
git gremote add origin <gitHubLink>
```

## Delete currently logged account
```bash
git credential-cache exit
```

## Push or upload our changes
```bash
git push -u origin main
```

## Logout if ever
```bash
git credential-manager github logout "username"
```