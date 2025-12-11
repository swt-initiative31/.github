# Initiative 31

> The project has been concluded with a demonstrator showing the feasibility of implementing SWT with an OS agnostic library, precisely Skia.
> It mitigated risks so that developing a production-ready SWT implementation based on Skia is just a matter of effort and not of conceptual or technical/technological risk.

> **The [final report is available here](documents/report/overall_report.md).**

## Summary

Initiative 31 is an evaluation project for the long-term sustainability of the Eclipse Standard Widget Toolkit (SWT), the Eclipse Platform, and products built on top it. SWT currently relies on three separate, OS-specific implementations, resulting in high maintenance effort and limited control over look-and-feel and customizability.
The project assessed a broad range of technologies for a new, OS-independent implementation of the SWT API. From this landscape, three candidates (GTK, Swing, and Skia) were explored through prototyping. The Skia-based approach, combined with custom-implemented widgets, emerged as the most promising path forward.
The Skia prototype was subsequently extended into a functional demonstrator capable of rendering all widgets using Skia while still launching and operating the Eclipse SDK. Additional targeted prototypes addressed key risks, including performance characteristics and event-handling behavior.

As a result, the project concludes with high confidence that a custom-widget SWT implementation powered by a rendering engine such as Skia is technically feasible. Completing this work to production quality is no longer a matter of conceptual or technological uncertainty, but rather of execution effort.
Initiative 31 was initiated and driven by members of the Eclipse IDE Working Group on a voluntary basis, without central funding. The resources available were insufficient to advance the demonstrator to a full production-ready implementation within the desired timeframe (approximately two years).

The project’s findings have been consolidated in a report which outlines the steps required to build a complete SWT implementation based on the demonstrator, and estimates the capacity needed to carry it out. The demonstrator, along with prototypes of all evaluated technologies, is publicly available on GitHub.


## Information

### Contributors
The project was primarily driven by companies in the [Eclipse IDE Working Group](https://eclipseide.org/working-group/), but of course every interested person was invited to join.
There was significant support from contributors that are not involved in the Eclipse IDE Working Group.

### GitHub Organization
This organization was set up as an umbrella for collaboratively working on prototypes and for sharing data and insights on the project.
That prototyping work was not about making actual changes to SWT but about evaluating whether any technology may be suitable to start an actual project for implementing SWT on that technology.
This is the main reason why this is not being done in the official SWT GitHub repository.
We also wanted to avoid giving the impression that because of this project no effort is being invested in the existing SWT projects.
Still, whatever developments were made during this project that are well placed in the official SWT, code was contributed back via pull requests.

Even though the work has officially been concluded, this organization remains open for everyone to keep working on the prototypes and eventually deriving a production-ready implementation out of it.

### Results
The [documents repository](https://github.com/swt-initiative31/documents) contains documentation of the progress and, in particular, of the results (including achievements, insights, risks) and an assessment for each of the investigated technologies.

It particularly include the [final report](documents/report/overall_report.md).

## Contacts

For general interest in the initiative or the Eclipse IDE Working Group driving it, please contact the working group's program manager:
- [Thomas Froment](mailto:thomas.froment@eclipse-foundation.org)

For interest in the initiative's technical details, please contact:
- [Heiko Klare](mailto:heiko.klare@vector.com)

The communication channels used during the project are still open, but may be closed at any future point in time:
- Matrix channel: https://chat.eclipse.org/#/room/#swt-initiative-31:matrix.eclipse.org 
- Slack channel: https://join.slack.com/t/initiative31/shared_invite/zt-2yef7gxqo-81A6WywphqWM~Bt1SioNhQ
