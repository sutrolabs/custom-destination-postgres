# Census Custom Destination: Postgres

This is experimental code for using [Census](https://www.getcensus.com/) to sync
data to a PostgreSQL destination. Depending on your Postgres version and
configuration, it is likely you'll need to fork and modify this sample in order
to talk to your database, list tables (objects) and columns (fields) correctly,
and implement the correct insertion logic - the sample code only allows
"upserts".

## Configuration

You can configure the Postgres connection in the source code, or by setting the
appropriate [environmental
variables](https://github.com/panates/postgresql-client/blob/master/DOCUMENTATION.md#112-environment-variables)
read by `postgresql-client`.


## Deploying to Netlify

The easy way

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/sutrolabs/custom-destination-postgres)

Advanced way

We recommend you follow [Netlify's specific instructions](https://www.netlify.com/blog/2021/04/19/announcing-native-typescript-support-for-netlify-functions/) for building and deploying typescript-based Netlify functions.