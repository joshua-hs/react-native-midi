# @motiz88/react-native-midi

An experimental [Web MIDI API](https://developer.mozilla.org/en-US/docs/Web/API/Web_MIDI_API) polyfill for React Native.

# Features

- [x] Android support
- [x] Web support
- [ ] iOS support
- [ ] Bluetooth scanning, virtual ports, and other nonstandard capabilities

# API

## `requestMIDIAccess(options?)`

Equivalent to [`Navigator.requestMIDIAccess`](https://developer.mozilla.org/en-US/docs/Web/API/Navigator/requestMIDIAccess) in the Web MIDI API. Respects the `sysex` option.

```typescript
import { requestMIDIAccess } from "motiz88/react-native-midi";

requestMIDIAccess().then((midiAccess) => {
  // Use midiAccess.inputs and midiAccess.outputs
});
```

Refer to the [Web MIDI API docs](https://developer.mozilla.org/en-US/docs/Web/API/Web_MIDI_API) for details.

# Installation

This package is not currently available for installation via npm.

<!--
> _NOTE:_ This package is experimental and may not work out of the box for you. Please [file an issue](https://github.com/motiz88/react-native-midi/issues) if you encounter a problem.

If using Expo: `expo install @motiz88/react-native-midi`
Otherwise: `npm install @motiz88/react-native-midi`
-->

<!-- TODO: Add iOS installation instructions when we have iOS support. -->

# Contributing

This project is in its early stages, but please feel free to look at the code and send PRs.
