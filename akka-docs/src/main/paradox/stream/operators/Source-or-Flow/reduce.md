# reduce

Start with first element and then apply the current and next value to the given function, when upstream complete the current value is emitted downstream.

@ref[Simple processing stages](../index.md#simple-processing-stages)

@@@div { .group-scala }

## Signature

@@signature [Flow.scala]($akka$/akka-stream/src/main/scala/akka/stream/scaladsl/Flow.scala) { #reduce }

@@@

## Description

Start with first element and then apply the current and next value to the given function, when upstream
complete the current value is emitted downstream. Similar to `fold`.


@@@div { .callout }

**emits** when upstream completes

**backpressures** when downstream backpressures

**completes** when upstream completes

@@@

