# pipex


Introducing pipes and here_doc in bash but coding them in c, the script should behave like bash.


## Installation


```bash
git clone https://github.com/trimize/42-pipex.git && cd 42-pipex
```

## Usage

To create the sorting executable :

```bash
make
```


Below is an example for the pipes :

```bash
./pipex infile cmd1 .. cmdn outfile
```

It will behave like < infile cmd1 | ... | cmdn > outfile
Of course the three dots are representing any amount of functions in between pipes

And here is the here_doc : 

```bash
./push_swap delimiter cmd1 cmd2 outfile
```

This will behave like bash, until the delimiter is passed stdin will be read.


## Grade

125
