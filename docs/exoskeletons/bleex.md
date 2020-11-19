# Berkeley Lower Extremity Exoskeleton

- type: lower extremity;
- total weight: 75 kg (exoskeleton and payload);
- degrees of freedom: 14 (7 on each leg);
- modules:
  - legs:
    - hip:
      - actuators: hydraulic cylinder for flexion/extension and
        abduction/adduction only;
      - sensors: two accelerometers on the extreme mounting points. One force
        sensor in the output mounting point of the hydraulic cylinder;
      - degrees of freedom: 3 (only abduction/adduction and flexion/extension
        axes pass through the human hip joint);
    - knee:
      - actuators: hydraulic cylinder for flexion/extension;
      - sensors: One force sensor in the output mounting point of the hydraulic
        cylinder;
      - degrees of freedom: 1
    - ankle:
      - actuators: hydraulic cylinder for flexion/extension;
      - sensors: two accelerometers on the extreme mounting points. One force
        sensor in the output mounting point of the hydraulic cylinder;
      - degrees of freedom: 3 (only flexion/extension axes pass through the
        human hip joint);
    - foot:
      - actuators: none, passive join only;
      - sensors: load distribution sensor, measure the amount of human weight on
        each leg. Also has two accelerometers on each foot;
      - degrees of freedom: 1
  - torso:
    - power source:
      - output power: 2.27 kW;

# References

[1] Adam Zoss, H. Kazerooni, Andrew Chu - On the Mechanical Design of the Berkeley Lower Extremity Exoskeleton (BLEEX), 2005.

<https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&ved=2ahUKEwixtK2hwoTtAhWbGLkGHbykBAYQFjABegQIBxAC&url=https%3A%2F%2Fbleex.me.berkeley.edu%2Fwp-content%2Fuploads%2Fhel-media%2FPublication%2FOn%2520the%2520Mechanical%2520Design%2520of%2520the%2520Berkeley%2520Lower%2520Extremity%2520Exoskeleton%2520-%2520IROS05.pdf&usg=AOvVaw06axkaBABCGt-a-nFn5HHa>
