Works with many Cisco CatXXXX-Switch-Series

**CLI**

    service unsupported-transceiver
    no errdisable detect cause gbic-invalid

**Hint - not all SFP+-Modula will be correct detected** 

Real-Life Szenario:

- Cat2960X detected a 10G-Finistar-SFP as 1G-SFP at Port G1/0/49
- Cat4500X deteced the same SFP+ correctly as unknown 10G-SFP+, but without any output for `show interface transiver`


