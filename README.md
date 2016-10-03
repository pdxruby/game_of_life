# pdx.rb Monthly Exercise

Every month, we're going to encourage people to take some time to reflect on
what we do as developers. We're going to focus on practicing our practice. To
code, merely to code. Not to make something, but to practice for the sake of
practice. Like sketches for artists, or scales for musicians, we're going to
create a space where we can just code for coding's sake.

## What is this?

The idea originally came from Code Retreats, but adapted to fit into a regular
short format rather than a day-long activity.

We're going to take a stab at creating Conway's Game of Life using as many best
practices as possible. This includes TDD, and, while not 100% required, pair
programming is highly encouraged. We'll have a short discussion to explain the
exercise, and any restrictions on the problem for the night.

Typically, we would do this exercise and erase all the code we create. After
all, a sketch is something used to work on our craft, not something to be
cherished. That said, sometimes it's useful to hold on to those sketches to
see how we've progressed. You're welcome to save the work, but whenever we do
this exercise without any restrictions, that is a time we encourage people to
save that code, to be able to reflect on how far we've come over time.

## Conway's Game of Life?

Yup... it's a pretty simple program that is fairly easy to explain.

There's four rules:

  1. Any cell that is alive, remains alive in the next generation with two or
  three neighbors.
  1. Any cell with three living neighbors becomes alive in the next generation,
  as if by reproduction.
  1. Any cell with fewer than two living neighbors dies, as if by starvation.
  1. Any cell with more than three living neighbors dies, as if by overpopulation.

That's it.

A starting population is set by the user as the initial generation on an N-by-N
grid. From that initial generation, those four rules govern how the grid evolves
over time.

You can read more about it here: https://en.wikipedia.org/wiki/Conway%27s_Game_of_Life

## Languages

Though we're a Ruby organization, we encourage people to learn new things to grow as
developers. We've supplied a Ruby setup in the Ruby folder, but would love to see
more languages get added and are accepting PRs that provide files and directories
to get people started with TDD in the given language.
