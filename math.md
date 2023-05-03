$$A^2 + B^2$$

This is an organic chemical equation: $$C_6H_{12}O_6 + 6O_2 \\rightarrow 6CO_2 + 6H_2O$$

One more example:

$$\cos(2\theta) = \cos^2 \theta - \sin^2 \theta$$


```mermaid
graph LR;
    A(Original C File) -->B((Preprocessor));
    B -->C[Modified C File];
    C(Modified C File) --> D{Compiler};
    D --> E[Assembly File];
    E(Assembly File) --> F{{Assembler}};
    F --> G[Object File];
    G((Object Files)) --> H{{Linker}};
    H --> I(Executable File);

```
