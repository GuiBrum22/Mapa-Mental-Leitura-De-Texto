# Mapa-Mental-Leitura-De-Texto


```mermaid
graph LR;
    A["📌 Fatores de Textualidade"] -->|1| B["🧩 Coerência"] 
    B --> B1["📖 Definição: Organização lógica das ideias"] 
    B1 --> B2["📊 Elementos: Progressão temática, consistência"] 
    B2 --> B3["📝 Exemplo: Manutenção do sentido no texto"] 

    A -->|2| C["🔗 Coesão"] 
    C --> C1["📖 Definição: Ligação entre palavras/frases"] 
    C1 --> C2["🛠️ Elementos: Conectivos, anáforas, elipses"] 
    C2 --> C3["📌 Exemplo: Uso de conjunções para conectar ideias"] 

    A -->|3| D["📝 Clareza"] 
    D --> D1["📖 Definição: Facilidade de compreensão"] 
    D1 --> D2["🛠️ Elementos: Simplicidade, organização textual"] 
    D2 --> D3["⚠️ Exemplo: Evitar ambiguidades e jargões complexos"] 

    A -->|4| E["✂️ Concisão"] 
    E --> E1["📖 Definição: Uso preciso das palavras"] 
    E1 --> E2["🚀 Elementos: Objetividade, evitar redundâncias"] 
    E2 --> E3["📝 Exemplo: Evitar repetições desnecessárias"] 

    A -->|5| F["📚 Correção (Variação Linguística)"] 
    F --> F1["📖 Definição: Norma culta e variações regionais"] 
    F1 --> F2["🛠️ Elementos: Gramática, ortografia, regionalismos"] 
    F2 --> F3["📌 Exemplo: Ajuste do vocabulário ao contexto"] 

    A -->|6| G["🎯 Intencionalidade"] 
    G --> G1["📖 Definição: Intenção comunicativa do autor"] 
    G1 --> G2["📌 Elementos: Objetivo do texto e público-alvo"] 
    G2 --> G3["📝 Exemplo: Textos persuasivos e informativos"] 

    A -->|7| H["💡 Informatividade"] 
    H --> H1["📖 Definição: Grau de novidade da informação"] 
    H1 --> H2["📊 Elementos: Conteúdo previsível ou inesperado"] 
    H2 --> H3["📰 Exemplo: Textos jornalísticos e acadêmicos"] 

    A -->|8| I["📜 Intertextualidade"] 
    I --> I1["📖 Definição: Referência a outros textos"] 
    I1 --> I2["🛠️ Elementos: Citações, paráfrases, alusões"] 
    I2 --> I3["📌 Exemplo: Referências literárias e culturais"] 

    A -->|9| J["✅ Aceitabilidade"] 
    J --> J1["📖 Definição: Aceitação pelo leitor"] 
    J1 --> J2["📌 Elementos: Adequação à expectativa do público"] 
    J2 --> J3["📝 Exemplo: Coesão e coerência alinhadas ao contexto"] 

    A -->|10| K["🌍 Situacionalidade"] 
    K --> K1["📖 Definição: Adequação ao contexto"] 
    K1 --> K2["📌 Elementos: Gênero textual, formalidade"] 
    K2 --> K3["📄 Exemplo: Linguagem formal em documentos oficiais"] 

    %% Estilizando os nós principais
    style A fill:#ffcc00,stroke:#333,stroke-width:3px
    style B fill:#ff6666,stroke:#990000,stroke-width:2px
    style C fill:#66ccff,stroke:#003366,stroke-width:2px
    style D fill:#99ff99,stroke:#006600,stroke-width:2px
    style E fill:#ff9966,stroke:#cc3300,stroke-width:2px
    style F fill:#cc99ff,stroke:#660099,stroke-width:2px
    style G fill:#ffff66,stroke:#999900,stroke-width:2px
    style H fill:#66ffcc,stroke:#009966,stroke-width:2px
    style I fill:#ff6699,stroke:#990033,stroke-width:2px
    style J fill:#6699ff,stroke:#0033cc,stroke-width:2px
    style K fill:#66ff66,stroke:#009900,stroke-width:2px

    %% Estilizando os sub-nós (Definição, Elementos, Exemplo)
    classDef subnode fill:#ffffff,stroke:#888,stroke-width:1.5px,font-size:12px;
    class B1,B2,B3,C1,C2,C3,D1,D2,D3,E1,E2,E3,F1,F2,F3,G1,G2,G3,H1,H2,H3,I1,I2,I3,J1,J2,J3,K1,K2,K3 subnode;
