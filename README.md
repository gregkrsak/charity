Charity
=======
I wrote this while I was bored, as a way to play with my gk-application gem. It opens an SSH connection, with the provided credentials, and runs a command on the server you specify.

```bash
./charity --donate "echo Hello, World" --to localhost --from root --password abc123
```

```
Welcome to Charity.
Charity: Running...
[BEGIN localhost: echo Hello, World]
  Hello, World
[END localhost: echo Hello, World]
Charity: Stopping...
Charity: Stopped.
```

Pull requests are welcome.
