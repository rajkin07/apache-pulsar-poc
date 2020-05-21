Installation
Apache Pulsar is available as a binary distribution. Let's start by downloading it:

wget https://archive.apache.org/dist/incubator/pulsar/pulsar-2.1.1-incubating/apache-pulsar-2.1.1-incubating-bin.tar.gz

When the download is complete, we can unarchive the zip file. The unarchived distribution will contain bin, conf, example, licenses and lib folder.

After that, we need to download the inbuilt connectors. These now ship as a separate package:

wget https://archive.apache.org/dist/incubator/pulsar/pulsar-2.1.1-incubating/apache-pulsar-io-connectors-2.1.1-incubating-bin.tar.gz

Unarchive the connectors and copy the Connectors folder in the Pulsar folder.

To start a standalone instance we can execute:

bin/pulsar standalone

