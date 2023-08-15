# Data Access

All of the data from CROCUS is open and freely available.

## Waggle-hosted Data
Most of the observations can be accessed using the Waggle cyberinfrastructure. We encourage people to check out the CROCUS node overview page, https://crocus.sagecontinuum.org/nodes. From there, you can select which location you are interested in, and find sample scripts to download the data. Data can be downloaded using the [`sage-data-client`](https://github.com/sagecontinuum/sage-data-client), with an example provided in the [WXT sensor cookbook](https://crocus-urban.github.io/instrument-cookbooks/notebooks/crocus_level1_node/vaisala_wxt536.html).


## Globus Data Transfer


For sensors not yet integrated into the Waggle cyberinfrastructure, we use [Globus](https://www.globus.org/) for data transfer.

Globus is a free software that allows to safely transfer data between two different points (endpoints). For example, the data from one instrument might be located on a computer at the observational site (one endpoint) and you would like to transfer that data to your local computer (another endpoint).

We encourage you to read over the how to get started guide from their documentation
- [Link to getting started with globus](https://docs.globus.org/how-to/get-started/)

<div class="admonition alert alert-warning">
    <p class="admonition-title" style="font-weight:bold">Warning</p>
    The datasets have not been quality corrected or controlled. This is raw data.
</div>

### Doppler LiDAR

The Doppler LiDAR instrument collects information about the velocity and scattering properties across different times and distances from the instrument, which in most cases for this project, is the ground.

We encourage you read the documentation about a Doppler LiDAR similar to the one used for CROCUS on the Atmospheric Radiation Measurement user facility page.
- [Link to information about the Doppler LiDAR instrument](https://www.arm.gov/capabilities/instruments/dl)

#### Link to the Doppler LiDAR data
Here is a link to the data:
- [Link to the LiDAR data globus endpoint](https://app.globus.org/file-manager?origin_id=d8da717e-ca5c-11ed-9622-4b6fcc022e5a&origin_path=%2F)

### SODAR

The SODAR (Sonic Detection and Ranging) wind profiler measures wind profiles and backscattered signal strength (from the ARM instrument guide).

We encourage you read the documentation about a Doppler LiDAR similar to the one used for CROCUS on the ARM user facility webpage.
- [Link to information about the SODAR](https://www.arm.gov/capabilities/instruments/sodar)

#### Link to the SODAR data
- [Link to the SODAR data globus endpoint](https://app.globus.org/file-manager?origin_id=160b4496-b6f4-11ed-a982-5f0e34a3cc4f&origin_path=%2F)
