## Chapter one - Setting it up

Setting up story and Rails. 
Setting up MySQL DB

## Chapter two - Planning and building our DB

Create the models for Cat, Owner

```yaml
Cat:
  name:
  bio:
  picture:
  breed:
```

```yaml
Owner:
  name:
```

Cat belongs to Owner, Owner has many Cats

Run Rail g models for each

## Chapter three - Install active admin gem

Place in gemfile.

Run:

```rails g active_admin:install Editor```

create a few cats and a few owners

## Create API

1. create namespace
2. create controllers
3. make them respond to with json only
