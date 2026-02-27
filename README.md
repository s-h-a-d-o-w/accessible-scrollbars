# accessible-scrollbars

## browsers

To be used with an extension such as [Stylus](https://chromewebstore.google.com/detail/stylus/clngdbkpkpeebahjckkjfobafhncgmne?pli=1) or [User Javascript or CSS](https://chromewebstore.google.com/detail/user-javascript-and-css/nbhcbdghjpllgmfilhnhkllmkecfmpld).

## vscode

1. Install [Custom CSS and JS Loader](https://open-vsx.org/extension/s-h-a-d-o-w/vscode-custom-css) and [Fix VSCode Checksums Next](https://marketplace.cursorapi.com/items?itemName=RimuruChan.vscode-fix-checksums-next) (Not on OpenVSX, yet. If you use some non-Microsoft VSCode-based IDE, build the .vsix from source yourself and/or like [this issue](https://github.com/RimuruChan/vscode-fix-checksums/issues/10)).
2. Following the instructions of these extensions, point to `styles.css` in some manner, then fix the VS Code checksums. The latter is to retain the security mechanism that VS Code offers.

This doesn't change the vertical scrollbars of the editor and terminal. For the editor, I recommend using the minimap. For the terminal, I have no solution. PRs are appreciated if you can find something.
