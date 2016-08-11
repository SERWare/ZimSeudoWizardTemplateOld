# ZimSeudoWizardTemplate

Modified HTML template for exporting content from a Zim (http://zim-wiki.org) Notebook as a "seudowizard guide" suitable for documents that illustrate the sequence of steps that a user must perform to achieve a goal (for example: product installation manuals).

I call it "seudowizard" because it does not work properly as a true wizard: it only shows the step sequence, but not strength the user to follow it. To simulate a wizard, each page of the Guide represents a step that contains ordered list of child steps that must be completed before continuing with the next.

The requirement is that each Zim Guide Page shows a somewhat decorated list of nested links (links prefixed by "+" to child pages) in the order required.

To assist the user, instead of showing the Zim Standard Content Index in the Menu Panel, the template shows a vertical breadcrumb path of links from root to the current page. Although it is not completely necessary, header and breadcrumb panel are generated as fixed panels while content can be scrolled, so that the user knows what step in the sequence is being made.

WARNING: Currently, the template does not support the option "export all pages to a single file.

No warranties or guarantees, please use this at your own risk.

#

