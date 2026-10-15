One-line: a modal for confirmations and short forms; the scrim is Almost Black at 55%.

```jsx
<Dialog title="Submit your project?" description="You can edit it until the deadline."
  footer={<><Button variant="ghost">Cancel</Button><Button>Submit</Button></>} onClose={close} />
```

The dialog is positioned against its nearest positioned ancestor, so wrap it in a `position: relative` container when demoing inside a card or frame.
