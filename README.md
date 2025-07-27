# glutothyination-data-processing

This is a Jupyter Notebook that converts 4 research papers findings in Dr. Ahn Young-Hoon's lab into SQL tables.
This is for my own usage to eventually develop a web application using NextJS. 

# Usage
You'll need Postgres running locally on your system, as well as Nix. Clone the repo and run `nix develop`. 
You'll also need to create a `.env` file which follows this format:

```
USER=
PASSWORD=
HOST=
PORT=
```

Once that's done, you can run `jupyter lab` or use VS Code with the Jupyter extension to run the notebook.