# Mapa-Mental-Leitura-De-Texto


```mermaid
graph TD;
    A["📌 Fatores de Textualidade"] -->|1| B["🧩 Coerência"] 
    A -->|2| C["🔗 Coesão"] 
    A -->|3| D["📝 Clareza"] 
    A -->|4| E["✂️ Concisão"] 
    A -->|5| F["📚 Correção (Variação Linguística)"] 
    A -->|6| G["🎯 Intencionalidade"] 
    A -->|7| H["💡 Informatividade"] 
    A -->|8| I["📜 Intertextualidade"] 
    A -->|9| J["✅ Aceitabilidade"] 
    A -->|10| K["🌍 Situacionalidade"] 

    B --> B1["📖 Organização lógica das ideias"] 
    B --> B2["📊 Progressão temática, consistência"] 
    B --> B3["📝 Manutenção do sentido no texto"] 

    C --> C1["🔗 Ligação entre palavras/frases"] 
    C --> C2["🛠️ Conectivos, anáforas, elipses"] 
    C --> C3["📌 Uso de conjunções para conectar ideias"] 

    D --> D1["🧐 Facilidade de compreensão"] 
    D --> D2["🛠️ Simplicidade e organização"] 
    D --> D3["⚠️ Evitar ambiguidades e jargões complexos"] 

    E --> E1["🎯 Uso preciso das palavras"] 
    E --> E2["🚀 Objetividade e evitar redundâncias"] 
    E --> E3["📝 Evitar repetições desnecessárias"] 

    F --> F1["📚 Norma culta e variações regionais"] 
    F --> F2["🛠️ Gramática, ortografia, regionalismos"] 
    F --> F3["📌 Ajuste do vocabulário ao contexto"] 

    G --> G1["🎯 Intenção comunicativa do autor"] 
    G --> G2["📌 Objetivo do texto e público-alvo"] 
    G --> G3["📝 Textos persuasivos e informativos"] 

    H --> H1["💡 Grau de novidade da informação"] 
    H --> H2["📊 Conteúdo previsível ou inesperado"] 
    H --> H3["📰 Textos jornalísticos e acadêmicos"] 

    I --> I1["📜 Referência a outros textos"] 
    I --> I2["🛠️ Citações, paráfrases, alusões"] 
    I --> I3["📌 Referências literárias e culturais"] 

    J --> J1["✅ Aceitação pelo leitor"] 
    J --> J2["📌 Adequação à expectativa do público"] 
    J --> J3["📝 Coesão e coerência alinhadas ao contexto"] 

    K --> K1["🌍 Adequação ao contexto"] 
    K --> K2["📌 Gênero textual e formalidade"] 
    K --> K3["📄 Linguagem formal em documentos oficiais"] 

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

    %% Estilizando os sub-nós
    classDef subnode fill:#ffffff,stroke:#888,stroke-width:1.5px,font-size:12px;
    class B1,B2,B3,C1,C2,C3,D1,D2,D3,E1,E2,E3,F1,F2,F3,G1,G2,G3,H1,H2,H3,I1,I2,I3,J1,J2,J3,K1,K2,K3 subnode;
