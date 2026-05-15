flowchart TD
A[Transactions Menu] --> B{Choice}

B -->|Deposit| C[Enter Account + Amount]
C --> D[Update Balance + Save File]
D --> A

B -->|Withdraw| E[Enter Account + Amount]
E --> F[Check Balance]
F --> G[Subtract Amount + Save File]
G --> A

B -->|Total Balance| H[Sum All Clients]
H --> A

B -->|Back| I[Return to Main Menu]
I --> A