```mermaid
graph TD
    subgraph Variables Independientes (Factores Psicológicos)
        X1[Responsabilidad Personal<br/>(Alta vs. Baja)<br/><i>Manipulación de Autojustificación</i>]
        X2[Marco de la Decisión<br/>(Pérdida vs. Neutral)<br/><i>Manipulación de Teoría Prospectiva</i>]
    end

    subgraph Variable Moderadora (Intervención)
        M[Intervención con GAI<br/>(Presente vs. Ausente)]
    end

    subgraph Variable Dependiente (Resultado)
        Y[Escalamiento del Compromiso<br/>(Cantidad invertida)]
    end

    %% Definición de las flechas (Hipótesis)
    X1 -- "H1 (+)" --> Y
    X2 -- "H2 (+)" --> Y
    
    %% La interacción entre X1 y X2 (H3) se representa con una flecha que sale de su combinación
    X1 -- "H3 (Interacción)" --- X2

    %% La moderación (H4 y H5) se representa con una flecha desde el moderador hacia la relación que modifica
    M -- "H4 (-)" ---> Y
    M -- "H5 (Modera la relación)" ---> X1
    

    %% Estilos para mayor claridad académica
    style X1 fill:#e3f2fd,stroke:#333
    style X2 fill:#e3f2fd,stroke:#333
    style M fill:#e8f5e9,stroke:#333
    style Y fill:#ffebee,stroke:#333
```
