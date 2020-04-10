# Delphi controller for emergency ventilators

The Delphi controller is an opensource device configurable for use as either a flexible user interface module or as a complete control system (and user interface) in emergency medical ventilators. Delphi is implemented as an oversized custom Arduino shield designed to be agnostic to the details of the air handling mechanism, sensing system, and other mechanical and electrical details of ventilators constructed for emergency use. As such, it is usable in whole or in part within virtually any emergency ventilator design.

## Design concept

We are guided by a belief that the global engineering and design community needs to modularize and standardize our efforts as we seek to develop safe opensource ventilators that can be used to help address expected equipment shortages during the coronavirus pandemic. Our initial contribution to this ecosystem is the Delphi controller. Delphi project development has been phased as follows:

1. **Delphi User Interface** - Our initial efforts are focused on the development and release of a flexible, clinician-validated user interface, comprising controller hardware and software, and a simple communications interface, which can be easily incorporated into other emergency ventilator projects. The Delphi user interface is intended to provide a clinician-validated standard user interface that is usable across a very wide range of emergency ventilator designs. By adopting the Delphi user interface standard, emergency ventilator design teams simplify the scope of their own project and help reduce barriers to adoption and use of their emergency ventilator by health care providers.

 2.	**Delphi Control System** - Subsequent efforts will focus on the development and release of an associated hardware-agnostic control system, comprising the same controller hardware, enhanced controller software, and a web-based application for configuration and calibration of individual ventilator designs. Configured as a control system, the Delphi controller will locally process incoming sensor data and actuate air handling motor output, in addition to handling user interface functionality. By adopting the Delphi control system standard, emergency ventilator design teams are freed to focus on the design and engineering challenges associated with their specific ventilator design, in addition to helping reduce barriers to adoption and use of their emergency ventilator by health care providers.

Although we are adopting a phased approach to development, the Delphi controller has been designed with the support of both sets of functionality in mind. Designers and engineers interested in utilizing Delphi are thus able to mirror our phased development approach if they choose: incorporating the Delphi controller into their systems first as a user interface module, and later switching to use of the Delphi controller as a fully functional, validated, and standardized control system. Among our priorities is the maintenance of active dialog with the community of healthcare providers who are treating Covid-19 patients, and continuously refining Delphi in response.
    
## Usage

Licensed under the GNU General Public License v3.0. All documents and diagrams are licensed under CC0.

## Project status

As of this writing, we are currently in the component testing and system development phase. We have concentrated our initial efforts on the design and development of the Delphi controller documented in the [Delphi Controller Functional Specification](Delphi_Controller_Functional_Specification.pdf), which can be used as either a standalone user interface module, or as an integrated control system for emergency medical ventilators.

As we begin prototype production and testing, our first objective is to finalize a completely functional user interface controller, including all hardware, software, and supporting materials. We have all materials on hand to manufacture working prototypes of the Delphi control board and hope to begin prototype production and clinician testing of a simulated system by the week of April 13th. 

Only at that point will we turn our efforts to the control system functionality of Delphi, developing all software, configuration applications, and other materials to support this use case.

We are publishing our progress towards these goals alongside our own development process in the hope that our work to date can help inform other efforts in this space.

## Contributing

This project is co-led by John Bennett (jkbco@outlook.com) and Jenny Filipetti (jenny.filipetti@gmail.com). We will update this section as we concretize support needs!

## Other ventilator module projects

[Ventmon](https://github.com/PubInv/ventmon-ventilator-inline-test-monitor) is a combined tester/monitor that would help clinicians validate untrusted ventilators in the case of a shortfall of commercial and professional equipment. Its creator [Public Invention](https://www.pubinv.org) is a major advocate of a modularized ecosystem model for ventilator design and is supporting the coordination of community efforts around benchmarking and breath analysis standards in addition to the Ventmon design.
