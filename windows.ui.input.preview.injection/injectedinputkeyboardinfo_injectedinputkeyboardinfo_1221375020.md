---
-api-id: M:Windows.UI.Input.Preview.Injection.InjectedInputKeyboardInfo.#ctor
-api-type: winrt method
---

<!-- Method syntax.
public InjectedInputKeyboardInfo.InjectedInputKeyboardInfo()
-->

# Windows.UI.Input.Preview.Injection.InjectedInputKeyboardInfo.InjectedInputKeyboardInfo

## -description
Creates a new [InjectedInputKeyboardInfo](injectedinputkeyboardinfo.md) object that is used to specify the keyboard input to inject.

## -parameters

## -remarks

> [!Important]
> The APIs in this namespace require the inputInjectionBrokered [restricted capability](https://docs.microsoft.com/windows/uwp/packaging/app-capability-declarations#special-and-restricted-capabilities).

Using input injection requires the following be added to the Package.appxmanifest:

- To `<Package>`
    - `xmlns:rescap="http://schemas.microsoft.com/appx/manifest/foundation/windows10/restrictedcapabilities"`
    - `IgnorableNamespaces="rescap"`
- To `<Capabilities>`
    - `<rescap:Capability Name="inputInjectionBrokered" />`


## -see-also

### Conceptual

[Gaze interactions and eye tracking in UWP apps](https://docs.microsoft.com/windows/uwp/design/input/gaze-interactions)

### Samples

- [Simulate user input through input injection](https://review.docs.microsoft.com/windows/uwp/design/input/input-injection?branch=kbridge-inputinjection)
- [Input injection sample (mouse to touch)](https://github.com/MicrosoftDocs/windows-topic-specific-samples/archive/uwp-input-injection-mouse-to-touch.zip)
- [Touch injection sample](http://go.microsoft.com/fwlink/p/?LinkID=267906)
- [Input: XAML user input events sample](http://go.microsoft.com/fwlink/p/?linkid=226855)

## -examples

