# pausable\_timer

[![CI](https://github.com/mateusfccp/pausable_timer/workflows/CI/badge.svg)](https://github.com/mateusfccp/pausable_timer/actions?query=branch%3Amain+workflow%3ACI+)
[![Pub Score](https://github.com/mateusfccp/pausable_timer/workflows/Pub%20Score/badge.svg)](https://github.com/mateusfccp/pausable_timer/actions?query=branch%3Amain+workflow%3A%22Pub+Score%22+)
[![Latest Dart version](https://github.com/mateusfccp/pausable_timer/actions/workflows/check-dart.yaml/badge.svg)](https://github.com/mateusfccp/pausable_timer/actions/workflows/check-dart.yaml)
[![pub package](https://img.shields.io/pub/v/pausable_timer.svg)](https://pub.dev/packages/pausable_timer)
[![pub points](https://img.shields.io/pub/points/pausable_timer)](https://pub.dev/packages/pausable_timer/score)
[![likes](https://img.shields.io/pub/likes/pausable_timer)](https://pub.dev/packages/pausable_timer/score)

A Dart timer that can be paused, resumed and reset.

`PausableTimer` aims to be as similar and compatible as possible with Dart's
`Timer`, while providing extra funcionality.

## How to use it

`PausableTimer` should work exactly the same as a regular `Timer`, but can be
paused, resumed and restarted with the respective methods (`.pause`, `.start`
and `.resume`).

There are also additional getters to check if the timer is active, paused,
expired or cancelled.

More detailed examples can be found in the [example](/example) folder.

