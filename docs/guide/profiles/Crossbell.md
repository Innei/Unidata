# Crossbell

[Crossbell](https://github.com/Crossbell-Box/).

You can initialize with `ipfsGateway` to get potentially faster speed.

## API

```ts
const profiles: Profiles = unidata.profiles.get(options: {
    source: 'Crossbell';
    identity: string;
});
```

## Live Demo

<Profiles :source="'Crossbell'" :defaultIdentity="'0xC8b960D09C0078c18Dcbe7eB9AB9d816BcCa8944'" />