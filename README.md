# TestThrift

Minimal setup to run [thrift_ql_ex](https://github.com/sambou/thrift_ql_ex).

First, install the dependencies with:

`mix deps.get`

Then run

`mix thrift_ql_ex.gen --thrift schema.thrift --out schema.graphql`

You should see the generated GraphQL schema file in the same folder.
