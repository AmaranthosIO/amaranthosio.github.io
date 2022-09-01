+++
title = "Build from nothing"
path = "build-from-nothing"
template = "empty.html"
+++
# Build from nothing

## Where do I start?

We must be able to start from nothing. This means no external dependencies.
We want simplicity of scale, therefore we need to abstract.
We also want something that can begin as a commodity and develop into more.
We need to define the way WE see the universe.

In [OOP](/library/oop), you may start thinking of [Objects](/library/objects).

In [DDD](/library/ddd) you may start looking for [Aggregates](/library/aggregates).

In [Event Sourcing](/library/event-sourcing.md) you may start looking at [Events](/library/event-storming).

For a data center, we have 3 particular areas of convergence:

  1. Network
  2. Compute
  3. Storage

These 3 areas form the fundamental idea of a `center for information access` and [data center infrastructure management](/library/dcim), they form the [Bounded Contexts](/library/bounded-context) of [infrastructure](/library/infrastructure). While we may have been taught to think of these ideas as `classes`, to the [composable information machine](/library/cim) they are simply [boundaries](/library/boundaries. For us, their definition is also an [Axioms](/library/axiom), something we defined and accept without argument. These end up as [Things](/library/things) as defined below and also lead us later into a [proof](/library/proof) system.

In a [Composable Information Machine](/library/cim), we have 3 base abstractions:

  1. Person
  2. Place
  3. Thing

*NOTE:* this is different than [inheritance](/library/inheritance). In [Rust](/library/rust), we use [Traits](/library/traits) and [Implementations](/library/implementations) to define constraints, behaviors and relationships.

These are not an encapsulation as in Object Oriented Classes. We are defining the 3 basic ideas that will permeate the entire system we build. We don't derive everything from `Object` as in [Object Oriented Programing](/library/oop).

We want to clarify where boundaries lie, not necessarily shove everything into a hierarchy or encapsulation. We will have to get used to this idea if coming from a purely OOP background. Functional Programming is a bit different.

We will define some more [Axioms](/library/axiom), meaning a definition, so we understand exactly what we are working with.

## Person

A person is human being. It can be a lot of other [things](/library/things), but for us, it roots as a human being. To assign properties, we will be extraordinarily limited, relying on [traits](/library/traits) and [implementations](/library/implementation) to build utility.

We will be avoiding definitions [such as this](https://schema.org/Person)

## Place

A place in a defined location in the universe. period.
Anything added to that is a [metric](/library/metric), or [topology](/library/topology), or something else which are [traits](/library/traits).

## Thing

A definable [concept].

These are the definitions we will use to begin, everything is evolutionary from here.

We have defined these in Rust.
