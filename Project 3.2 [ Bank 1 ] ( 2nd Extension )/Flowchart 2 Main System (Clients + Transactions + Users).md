flowchart TD
A[Start Program] --> B[Load Clients from File]
B --> C[Show Main Menu]

C --> D{User Choice}

D -->|1| E[Show Clients List]
E --> C

D -->|2| F[Add New Client]
F --> C

D -->|3| G[Delete Client]
G --> C

D -->|4| H[Update Client]
H --> C

D -->|5| I[Find Client]
I --> C

D -->|6| J[Transactions Menu]
J --> K{Transaction Choice}

K -->|Deposit| L[Add Money]
K -->|Withdraw| M[Withdraw Money]
K -->|Total Balance| N[Show Total Balance]
K -->|Back| C

L --> C
M --> C
N --> C

D -->|7| O[Exit Program]
O --> P[End]