## Linux Command GPT (lcg)
Get Linux commands in natural language with the power of ChatGPT.
This is a rewrite in Python, mostly done with GPT-4.

### Installation
This comes with a shell script predone, just link to your $PATH.
```bash
> git clone https://github.com/Zack-Fisher/linux-command-gpt-python
> cd linux-command-gpt-python
> sudo ln lcg /usr/bin/lcg
> lcg
```

### API key
Note: this script uses the environment variable OPENAI_API_KEY.
Run the command
```bash
> export OPENAI_API_KEY=<your api key here>
```
to set that up.
If you want the export to be permanent, add the line to your ~/.zshrc or ~/.bashrc.

### Example Usage

```bash
> lcg I want to extract linux-command-gpt.tar.gz file
Completed in 0.92 seconds
┌────────────────────────────────────┐
│ tar -xvzf linux-command-gpt.tar.gz │
└────────────────────────────────────┘
Are you sure you want to execute the command? (y/n):
```

### Options
```bash
> lcg [options]

--help         output usage information
--version      output the version number
```
