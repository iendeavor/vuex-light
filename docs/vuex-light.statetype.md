<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [vuex-light](./vuex-light.md) &gt; [StateType](./vuex-light.statetype.md)

## StateType type


<b>Signature:</b>

```typescript
export declare type StateType<S extends StateOption> = Ref<{
    [P in keyof S]: S[P];
}>;
```
<b>References:</b> [StateOption](./vuex-light.stateoption.md)
