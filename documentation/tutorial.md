
## MD Solvation Shell Tab





#### Name Field

An optional name to be given to the structure on import.

#### Topology File Path

The file path to the toplogy file for import.
See the [table of supported topology formats](https://docs.mdanalysis.org/stable/documentation_pages/topology/init.html#supported-topology-formats) for the formats that should be importable by Molecular Nodes.

#### Trajectory File Path

The file path to the trajectory file for import.
See the [table of supported trajectory formats](https://docs.mdanalysis.org/stable/documentation_pages/coordinates/init.html#id2) for the formats that should be importable by Molecular Nodes.

#### Frame Import Options

-   Start Frame: The first possible frame from the coordinate file to be imported into Blender

-   Interval: Imports every *n* th frame from the trajectory.
    1 will import all frames from the trajectory.

-   End Frame: The last possible frame from the coordinate file to be imported into Blender.

#### Nanometre Scale

Inside of structure files, the base unit is usually 1 Å, which will become 1 m inside of Blender and 1 nm will become 10 m.
To scale things down to a more manageable size we re-scale the structure so that 1 nm will become 1 m.

![](images/CleanShot%202022-05-19%20at%2013.21.32@2x.png)

