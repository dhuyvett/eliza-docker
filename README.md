# eliza-docker

Chatbots are all the rage these days, so here is one in a docker image

# Building

```bash
$ docker build -t eliza -f <base os>/<version>/Dockerfile .
```

# Running

```bash
$ docker run -it --rm  eliza
Eliza: Welcome.
You: I amm glad to be here
Eliza: What makes you glad just now?
You: 
```

