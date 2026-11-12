# SBMAA ledger categorization page

Web page for categorizing the SBMAA master ledger: https://sbmedicalorg.github.io/ledger-app/

This repository holds only the page. It contains no financial data. The ledger lives in the private
repository `sbmedicalorg/budget`; the page loads and saves it through the GitHub API using each person's own
fine-grained token (Contents: Read and write on `sbmedicalorg/budget`), which stays in their browser.
