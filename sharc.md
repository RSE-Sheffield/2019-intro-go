## SHARC and conda

`conda` can do lots of things, not just Python. On `sharc` with `conda`:

    # Per http://docs.hpc.shef.ac.uk/en/latest/sharc/software/apps/python.html
    # the usual thing to start using conda on sharc:
    module load apps/python/conda

    # Create a conda environment (you can choose a different name if you want)
    conda create --name my-go-stuff
    # ... activate it.
    . activate my-go-stuff

    # Per https://anaconda.org/conda-forge/go
    # install Go.
    conda install --channel conda-forge go

Now you should be able to run the Go compiler:

    go

You should see a help message.

The conda environment you created will persist.
In a future session you only need conda and to activate the environment:

    module load apps/python/conda
    . activate my-go-stuff


## On the Web

An interactive web page for small Go snippets:

https://play.golang.org/

## First steps

There is a tour with interactive exercises: https://tour.golang.org/welcome/1

## Next steps

Effective Go https://golang.org/doc/effective_go.html
 discusses how to write Go like a Go programmer.

_GoSheffield_ is Sheffield's burgeoning Go meetup: https://www.meetup.com/GoSheffield/


## Finally

Please abide by the Go Community Code of Conduct when using Go.

https://golang.org/conduct

Enjoy.
