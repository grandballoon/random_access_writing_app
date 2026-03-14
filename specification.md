This repo represents the code and roadmap for a writing application premised on a single idea: random access (in computer science terms, O(1), or as near as we can get it)
to any given note. The inspiration for this application is Robert Pirsig's description of his note-taking system in Lila: An Inquiry into Morals.

The high-level specification for this application is as follows:

- It is a cross-platform application, running on Mac, Windows, iOS, and Android.
- It does not feature publish-to-the-web, manuscript-formatting, or any other publishing features; its only focus is facilitating access to written material, and writing.
- It includes an integration with Git, meaning that it retains snapshots of any given note's entire history. The UI for interacting with this snapshot history is TBD.
- Any given page is about the size of a standard notecard (although it will appear somewhat larger on a desktop). This means the page length is shorter than a standard 8.5x11 printer paper, meaning that the user never has to scroll the view the full amount of text on a page.
- It includes no affordances for bidirectional linking between cards or organizing cards into folders. The only user-specified metadata is a tag.
- Tags can be individual (#todo) or nested (#wedding/venue/booking/todo). 
