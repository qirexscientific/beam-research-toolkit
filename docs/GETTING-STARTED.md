# Getting started (including if you are new to GEANT4)

## What GEANT4 is, in one paragraph

GEANT4 is a widely used toolkit for simulating how particles travel through matter — detectors, shielding, tissue, spacecraft walls. Labs around CERN and elsewhere rely on it. It is also famous for a painful first week: compilers, data files, physics lists, and a lot of C++.

Beam Research Toolkit runs a managed GEANT4 for you inside a desktop app. You still benefit from the same class of simulation. You do not have to become a GEANT4 build engineer first.

## First hour

1. Download the [Linux or macOS build](https://qirexscientific.com/downloads.html).
2. Launch it. You have **14 days of full access**.
3. Open a configuration, run a beam, open the explorer and a dose view.
4. Export something your other tools understand (CSV, ROOT, ParaView / VTU, DICOM RT Dose).

If a button does nothing or a view is empty, [open a bug](../issues/new?template=bug.yml). If you do not know which view to trust, [ask a question](../issues/new?template=question.yml).

## After the trial

Subscribe **inside the app**: €24 / month or €240 / year. The website cannot start that subscription.

## Good habits

- Save the configuration that produced a plot you care about.
- Treat Beam output like any other simulation: check units, geometry, and that you exported the run you think you exported.
- Do not upload other people’s restricted data into a public GitHub issue.

## You do not need to pretend you are a staff physicist

Curious people tinker with public collider plots and detector pictures every day. Some of that tinkering is sloppy. Beam is meant to be a *high-quality* on-ramp: real GEANT4 under the hood, readable views on top, an issue tracker where “I am new” is an acceptable first sentence.
