# partcad-standard-metric-nema

## Interfaces

* ``nema-17-motor-mount``

  NEMA 17 motor mount. Defines the layout and depth of mounting holes.

* ``nema-17-motor``

  NEMA 17 motor. It inherits the motor mount and adds the shaft.

* ``nema-17-bracket``

  NEMA 17 mounting bracket. It defines the mounting holes location.
  Mates with ``nema-17-motor-mount``.

* ``nema-17-bracket-3mm``

  3mm thick NEMA 17 mounting bracket.
  It specifies the location of the mounting holes as well as the thickness of the bracket.
  Mates with ``nema-17-motor-mount``.
