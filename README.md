![](../../workflows/gds/badge.svg) ![](../../workflows/docs/badge.svg) ![](../../workflows/test/badge.svg) ![](../../workflows/fpga/badge.svg)

# ASICLAB Verilog Project Template

- [Read the documentation for project](docs/info.md)

## What is ASICLAB Verilog Project?

ASICLAB Verilog Project is an educational project that aims to make it easier and cheaper than ever to get your digital and analog designs implementation.

## Set up your Verilog project

1. Add your Verilog files to the `src` folder.
2. Edit the [info.yaml](info.yaml) and update information about your project, paying special attention to the `source_files` and `top_module` properties. 
3. Edit [docs/info.md](docs/info.md) and add a description of your project.
4. Adapt the testbench to your design. See [test/README.md](test/README.md) for more information.

The GitHub action will automatically build the ASIC files using [OpenLane](https://www.zerotoasiccourse.com/terminology/openlane/).

## Enable GitHub actions to build the results page

## What next?

- Edit [this README](README.md) and explain your design, how it works, and how to test it.
