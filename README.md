# Commercial-Proposal-Code
Google Apps Script, to replace in a commercial proposal information on a Google Sheets

Make a Google Sheets sheet, go to Extensions > Apps Script, paste code.
Name the automation tab whatever you want, substitute its name in the code.
You are able to create different sheets and use it for diferent data processing and calculations.

Automation sheet should follow the format:

```
    |    A    |    B    |    C    |
1   | Keyword | Keyword | Keyword |
2   | Replace | Replace | Replace |
```

As many Keywords as you want, one replacement per Keyword.
In the model doc, anything in the format double curly bracket + keyword: {{Keyword}} will be replaced by the replacement text, following format, regardless of text size.
The code creates a copy of the model, replaces the keywords and renames to whatever you want.
