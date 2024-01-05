OpenTelemetry .NET
Slack codecov.io Nuget NuGet Build

The .NET OpenTelemetry client.

Supported .NET Versions
Packages shipped from this repository generally support all the officially supported versions of .NET and .NET Framework (an older Windows-based .NET implementation), except .NET Framework 3.5. Any exceptions to this are noted in the individual README.md files.

Project Status
Stable across all 3 signals i.e. Logs, Metrics, and Traces.

See Spec Compliance Matrix to understand which portions of the specification has been implemented in this repo.

Getting Started
If you are new here, please read the getting started docs:

Logs: ASP.NET Core | Console
Metrics: ASP.NET Core | Console
Traces: ASP.NET Core | Console
This repository includes multiple installable components, available on NuGet. Each component has its individual README.md file, which covers the instruction on how to install and how to get started. To find all the available components, please take a look at the src folder.

Here are the most commonly used components:

OpenTelemetry .NET API
OpenTelemetry .NET SDK
Here are the instrumentation libraries:

ASP.NET Core
gRPC client: Grpc.Net.Client
HTTP clients: System.Net.Http.HttpClient and System.Net.HttpWebRequest
SQL clients: Microsoft.Data.SqlClient and System.Data.SqlClient
Here are the exporter libraries:

Console
In-memory
OTLP (OpenTelemetry Protocol)
Prometheus AspNetCore
Prometheus HttpListener
Zipkin
See the OpenTelemetry registry and OpenTelemetry .NET Contrib repo for more components.

Troubleshooting
See Troubleshooting. Additionally check readme file for the individual components for any additional troubleshooting information.

Extensibility
OpenTelemetry .NET is designed to be extensible. Here are the most common extension scenarios:

Building a custom instrumentation library.
Building a custom exporter for logs, metrics and traces.
Building a custom processor for logs and traces.
Building a custom sampler for traces.
Contributing
See CONTRIBUTING.md

We meet weekly on Tuesdays, and the time of the meeting alternates between 9AM PT and 4PM PT. The meeting is subject to change depending on contributors' availability. Check the OpenTelemetry community calendar for specific dates and for Zoom meeting links.

Meeting notes are available as a public Google doc. If you have trouble accessing the doc, please get in touch on Slack.

Maintainers (@open-telemetry/dotnet-maintainers):

Alan West, New Relic
Mikel Blanchard, Microsoft
Utkarsh Umesan Pillai, Microsoft
Approvers (@open-telemetry/dotnet-approvers):

Cijo Thomas, Microsoft
Reiley Yang, Microsoft
Vishwesh Bankwar, Microsoft
Triagers (@open-telemetry/dotnet-triagers):

Martin Thwaites, Honeycomb
Emeritus Maintainer/Approver/Triager:

Bruno Garcia
Eddy Nakamura
Liudmila Molkova
Mike Goldsmith
Paulo Janotti
Robert Pająk
Sergey Kanzhelev
Victor Lu

Donate: 0xf07Bc539c98065B7f21456f424E23045aD39280B (ERC20)
