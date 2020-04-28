# prettier-css-formatting-problem-demo

Repo showcasing the problem for reported issue.

If CSS file has a string value which is split into multiple lines, newline character `\` inside the string is not handled correctly, affecting the rest of the formatting from that point forwards. Reference: https://drafts.csswg.org/css-values-3/#strings

The CSS in `cssproblem.css` passes the W3C validation at https://jigsaw.w3.org/css-validator/ but the content is rendered as shown in screenshot `cssproblem.png`.

Link to [prettier-vscode issue](https://github.com/prettier/prettier-vscode/issues/1359).
