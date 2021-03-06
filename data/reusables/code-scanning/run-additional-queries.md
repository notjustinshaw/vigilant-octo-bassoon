When you use {% data variables.product.prodname_codeql %} to scan code, the {% data variables.product.prodname_codeql %} analysis engine generates a database from the code and runs queries on it. For more information, see "[About {% data variables.product.prodname_code_scanning %}](/github/finding-security-vulnerabilities-and-errors-in-your-code/about-code-scanning#about-codeql)."

{% data variables.product.prodname_codeql %} analysis uses a default set of queries, but you can specify more queries to run, in addition to the default queries. The queries you want to run must belong to a {% data variables.product.prodname_ql %} pack in a repository. For more information, see "[About {% data variables.product.prodname_ql %} packs](https://codeql.github.com/docs/codeql-cli/about-ql-packs/)."

Queries must only depend on the standard libraries (that is, the libraries referenced by an `import LANGUAGE` statement in your query), or libraries in the same {% data variables.product.prodname_ql %} pack as the query. The standard libraries are located in the [github/codeql](https://github.com/github/codeql) repository. For more information, see "[About CodeQL queries](https://codeql.github.com/docs/writing-codeql-queries/about-codeql-queries/)."

You can specify a single _.ql_ file, a directory containing multiple _.ql_ files, a _.qls_ query suite definition file, or any combination. For more information about query suite definitions, see "[Creating {% data variables.product.prodname_codeql %} query suites](https://codeql.github.com/docs/codeql-cli/creating-codeql-query-suites/)."


