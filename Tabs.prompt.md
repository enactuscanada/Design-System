One-line: switch between sibling views; the active tab is bold with a 3px Enactus Gold underline.

```jsx
<Tabs items={[{value:'about',label:'About'},{value:'teams',label:'Teams'}]} value={tab} onChange={setTab} />
```

The gold underline is the system's standard "you are here" signal — reuse it for nav rather than gold text or gold pills.
