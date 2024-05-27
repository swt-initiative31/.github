# Initiative 31

## Why This Project?

In this project, we are going to evaluate options to modernize [Eclipse SWT](https://github.com/eclipse-platform/eclipse.platform.swt/) in terms of improved look & feel and customizability while reducing maintenance effort. The outdated appearance of Eclipse SWT applications, in particular on Windows, is a significant problem mentioned by users and also for companies developing RCP-based products. In addition, the necessity to develop and validate changes and improvements three times (for each of the existing implementations) together with being restricted to what is possible with the least common denominator across the three operating system APIs limits the opportunities for progress in Eclipse SWT.

This project will evaluate some different options for replacements to overcome these limitations. 
It is currently at the beginning of a prototyping phase, in which different technologies will be evaluated in terms of whether they are suitable candidates to be used in an SWT implementation.

The project is primarily driven by companies in the [Eclipse IDE Working Group](https://eclipseide.org/working-group/), but of course every interested person is invited to join.


## Why This GitHub Organization?

The prototyping phase is not about making actual changes to SWT but about evaluating whether any technology may be suitable to start an actual project for implementing SWT on that technology. 
This is the main reason why this is not being done in the official SWT GitHub repository.
We also want to avoid giving the impression that because of this project no effort is being invested into the existing SWT projects.
Still, whatever developments are made during this project that are well placed in the official SWT code will be contributed back via pull requests.

This organization serves as an umbrella for sharing data and insights on the work of this initiative, which, in particular, includes the collaborative work on prototypes.
