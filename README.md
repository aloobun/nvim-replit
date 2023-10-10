# nvim-replit


This inference code uses a ggml quantized model and generate a code response based on the given instructions.

Save file at ```~/.config/nvim/rplugin/python/t2t.py```

Next, ```:UpdateRemotePlugins`` every time a remote plugin is installed, updated, or deleted.

The user can invoke the plugin by typing ```:T2T``` followed by the instruction. 

Example,
```
:T2T Write a program in C to add two numbers
```

This was a stupid experiment. I wanted to learn more about plugin development than running a inference code on CPU.

There are better implementations than this.
