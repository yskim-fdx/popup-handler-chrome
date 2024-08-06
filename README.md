# Popup handler chrome - UiPath
- Use modern activity
- Selector 에서 `wnd` node 사용하여, window application 으로 사용 
```csharp
string.Format("<wnd app='chrome.exe' title='{0}' />", in_ChromeTitle)
```
