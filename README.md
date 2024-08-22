This is a modified basis of the Hibridon code that can be dowloaded at https://github.com/hibridon/hibridon.

Hibridon is a program package to solve the close-coupled equations which occur in the quantum treatment of inelastic atomic and molecular collisions. Gas-phase scattering, photodissociation, collisions of atoms and/or molecules with flat surfaces, and bound states of weakly-bound complexes can be treated

The full documentation is available on https://github.com/hibridon/hibridon/wiki

By replacing the hiba30_astp3.F90 basis by the one supplied here, the Hibirdon code can be compiled as usual.

This modification is on the EMAX option. This option cuts out of the basis any channels with an energy greater than EMAX. However, this option only applies on the energy levels of monomer 1, and not on all channels of the system. This modification allows the EMAX option to be applied on all channels of the basis.

This modification is simple and can be applied on other Hibridon bases, and is just provided as an example.
