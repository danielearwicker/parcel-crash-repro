Clone, `yarn` and then `yarn start`.

Parcel crashes with SIGBUS on macOS or just silently exits on Windows 10.

If you change:

    $variable-containing-calc: calc(0.5rem - 2px);

to

    $variable-containing-calc: 0.5rem;

It works fine.
