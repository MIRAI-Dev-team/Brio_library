# Brio Library

The tool is thought to be used for inspecting machine learning systems that 
could be affected by biases in their predictions. 

A typical scenario where the tool can help is the following: consider a database 
containing details of individuals, with their age, gender, and level of education. 
Consider an algorithm which tries to predict whether each of them is likely to default on credit. 
The user wishes to check if age is a sensitive factor in such prediction. 
The user feeds the tool our dataset, the output of the run of the predictive algorithm, and mark 
the feature of age as sensitive. Currently the tool allows the user to compare either how the 
behaviour of the algorithm with respect to age differs from an ``optimal'' behaviour 
(in this case, the user might consider optimal the case where each age group equally succeeds), 
or how different age groups perform with respect to one another.

These two analyses take the names of FreqVsRef and FreqVsFreq, described in a section below. 

## License

This work is licensed under a Creative Commons
Attribution-NonCommercial-NoDerivatives 4.0 International License (CC
BY-NC-ND 4.0).

This means you are free to:

-   **Share** --- copy and redistribute the material in any medium or
    format

Under the following terms:

-   **Attribution** --- You must give appropriate credit, provide a link
    to the license, and indicate if changes were made. You may do so in
    any reasonable manner, but not in any way that suggests the licensor
    endorses you or your use.
-   **NonCommercial** --- You may not use the material for commercial
    purposes.
-   **NoDerivatives** --- If you remix, transform, or build upon the
    material, you may not distribute the modified material.

You may not apply legal terms or technological measures that legally
restrict others from doing anything the license permits.

### Full License Details

The full legal text of the CC BY-NC-ND 4.0 license is available at:\
<https://creativecommons.org/licenses/by-nc-nd/4.0/legalcode>

### Summary of License Terms

A human-readable summary of the license (which is not a substitute for
the full license) can be found at:\
<https://creativecommons.org/licenses/by-nc-nd/4.0/>

## Usage
The main functionalities of the tools are also available as python library, named `brio`. 
You can install it via pip, doing `pip install brio`. 
The bias detection analyses can be performed directly using the `FreqVsRefBiasDetector` and `FreqVsFreqBiasDetector` 
classes interfaces. 

## Contact

For development inquiries: dev@mirai.systems
For research collaborations: research@mirai.systems

## Resources

Additional resources, documentation, and support materials are available at:
https://mirai.systems/resources/

**Please ensure you understand and comply with the CC BY-NC-ND license
terms before using, sharing, or modifying this work.**
