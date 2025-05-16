# Replicator [![Build status](https://ci.appveyor.com/api/projects/status/ggbm45lhwipiwmfk/branch/dev?svg=true)](https://ci.appveyor.com/project/datalust/seq-app-replication/branch/dev)

The `Seq.App.Replication` plug-in, which forwards incoming events to another Seq server. Requires Seq 2025.1+.

This app can be used to implement store-and-forward to another Seq instance, for limited disaster recovery. For reliable built-in disaster recovery, 
see [Clustering Overview](https://docs.datalust.co/docs/clustering-overview) in the Seq documentation.

> [!NOTE]
>
> This app does not fully support traces or OpenTelemetry envelope properties like `@Resource` and `@Scope`. See [Seq.App.Relay](https://github.com/datalust/seq-app-relay) for an alternative implementation that supports all current Seq features.

## Getting started

Get started with these [instructions for installing Seq apps](https://docs.datalust.co/docs/installing-output-apps).