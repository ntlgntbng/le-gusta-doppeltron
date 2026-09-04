## **Description**

A clear and concise summary of the changes introduced in this pull request. Explain the problem being solved or the feature being implemented.

Fixes \#(issue)

## **Type of Change**

Please delete options that are not relevant:

* \[ \] **fix**: Bug fix (non-breaking change fixing an issue)  
* \[ \] **feat**: New feature or hardware telemetry module  
* \[ \] **perf**: Performance optimization (e.g., canvas rendering efficiency)  
* \[ \] **docs**: Documentation updates  
* \[ \] **refactor**: Code restructuring without functionality changes  
* \[ \] **style**: Formatting or CSS theme adjustments

## **Changes Made**

* List specific technical or UI changes made in this PR.  
* Mention any DSP audio routing, canvas rendering, or formula updates.

## **Verification & Testing Checklist**

Please verify the following before requesting a review:

* \[ \] **Web Audio Safety:** Updates to gain/frequency parameters use setTargetAtTime or ramp functions without pop/click artifacts.  
* \[ \] **Canvas DPI Scale Isolation:** Canvas context renders use ctx.setTransform(dpr, 0, 0, dpr, 0, 0\) to prevent Retina/4K scaling drift.  
* \[ \] **Cross-Browser Verification:** Tested and working on Chromium, Firefox, and WebKit (Safari/iOS) engines.  
* \[ \] **Responsive Design:** Layout verified across mobile, tablet, and desktop display resolutions.  
* \[ \] **Single-File Integrity:** Application logic and styles remain self-contained within index.html.

## **Screenshots / Visual Proof**

If applicable, attach screenshots, canvas output recordings, or audio telemetry logs demonstrating the changes:

| Before | After |
| :---- | :---- |
| *(Image or N/A)* | *(Image or N/A)* |

## **Additional Notes**

Add any extra context, performance benchmarks, or deployment considerations here.