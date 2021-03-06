# EventSourcery Generators

An opinionated CLI tool for building event sourced systems with EventSourcery.

## Getting started

Generate a new event sourcery application:

```sh
$ eventsourcery new recipe_book
```

Generate a new aggregate, command and event:

```sh
$ eventsourcery generate:command recipe add
```

Generate a query and projection that subscribes to events:

```sh
$ eventsourcery generate:query active_recipes recipe_added
```

Generate a reactor that subscribes to events:

```sh
$ eventsourcery generate:reactor recipe_publisher recipe_added recipe_deleted
```

## References

For more information, check out the `event_sourcery` repository here:
<https://github.com/envato/event_sourcery>

