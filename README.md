# Example Application

This is an example application using Elixir, Cowboy and Lager.

# Installation & Setup

Clone the repository and then use the [Elixir Mix Tool][mix] to get the dependencies:

    mix deps.get

Now you can compile the project:

    mix compile

# Usage

Start the interactive shell and run the Example.start method to run it:

    iex(1)> Example.start

You should get shell output similar to:

    22:24:20.423 [info] Application lager started on node nonode@nohost
    22:24:20.427 [info] Application cowboy started on node nonode@nohost
    22:24:20.427 [info] Application example started on node nonode@nohost

Use the exit method to stop the application and exit the shell:

    iex(2)> Example.exit


[mix] http://elixir-lang.org/getting_started/mix.html
