# CQL support for VS Code

## This is a language extension for the Cassandra CQL language.
This is an extension for working with Cassandra CQL. This extension supports syntax highlighting. Table definitions found will allow intellisense to work. This extension will find symbols for tables and columns. All keywords have intellisense. There are snippets for basic CQL statements.

###Features
   - Currently Supports:
    - Syntax Highlighting
    - Brackets
    - Comments
    - Intellisense 
    - Keywords *(SELECT, ALTER, UUID, etc)*
    - Table Names* 
    - Column Names*
    - Snippets (SELECT, CREATE TABLE|KEYSPACE|TRIGGER|TYPE|INDEX, UPDATE)
    - CQL Statement Execution
 
###Configuration
- Configuration Keys
 - **cql.address** *(string)*: IPAddress or hostname of Cassandra endpoint for the Execute command. *Default is 127.0.0.1*
 - **cql.port**: *(integer)*: Port of the Cassandra endpoint for the Execute command. *Default is 9024*
      

### Other
   - Task List:
    - ~~Execute Statements~~ (done)
    - ~~Configure extension~~ (done)
    - Context for Intellisense *(some)* 
    - ~~Better Internal Structure~~ (done)
    - Symbols functionality
    - Document
    - Workspace
    - Search Cassandra for symbols
    - ~~Better Syntax Highlighting~~ (done)
    - Moving task to Issues


### For more information
* [project on github](https://github.com/lawrencekgrant/vscode-cql)

*(Table and Column names come from CREATE scripts that have been opened.)*

### Build Status:
[![Build Status](https://travis-ci.org/lawrencekgrant/vscode-cql.svg?branch=master)](https://travis-ci.org/lawrencekgrant/vscode-cql)

**Enjoy!** 