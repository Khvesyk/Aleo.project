# Aleo.project

## Run Guide

To run this program, run:
```bash
leo run play

or 

./run.sh
```

## Execute Guide

To execute this program, run:

```bash
leo execute play
```

## The leo help command

Open a new terminal window and type: 
```bash
leo --help
``` 
to confirm that Leo is installed.

## The leo account command

```bash
leo account new
```
Continue in your existing terminal window and type 
```
leo account new
```
you should see something similar to the following output:
```bash
Private Key  APrivateKey1zkpAeeSTY6CuV2ahuJsHLqBFEChK3NnKxLqDyFoMQVmi1Ru
View Key  AViewKey1cuV5NU4WgkHezc6fFFduECwrpGg8knqyb78YFJVmhhMT
Address  aleo14hmf2rfh5nne6m7wsqlklqzcagh2tjydecvjycgj80snnns9svqsyjzsll
```

## The leo example command

Continue in your exsiting terminal window and type:
```bash
leo example $NAME
```
You should see the following output:
```bash
Create a new Leo example package in a new directory
    
Usage: leo example [OPTIONS] <COMMAND>
    
Commands:
  lottery    A public lottery program
  tictactoe  A standard tic-tac-toe game program
  token      A transparent & shielded custom token program
  help       Print this message or the help of the given subcommand(s)
    
Options:
  -d                 Print additional information for debugging
  -q                 Suppress CLI output
      --path <PATH>  Optional path to Leo program root folder
  -h, --help         Print help
```

Choose one of the examples, and create it using the leo example command like so: 

``` bash
leo example tictactoe
```

## The leo run command
``` bash
leo run $FUNCTION
```
Navigate to the root of your Leo project's folder using the 
```bash
cd
```
command, i.e., 
```
cd tictactoe
```
To run your new Leo example, refer to the included 
```
README.md
```
file, which you can find in the root of your newly created project's folder.

An example 
```
leo run
```
command for the tictactoe application is 
```
leo run new
```
which creates a new game board.
 
