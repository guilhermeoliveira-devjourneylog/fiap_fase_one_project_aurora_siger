## Scenario: Execution 

Operator -- System: program

System -- Telemetry: get data

Telemetry -- System: ingestion data for dataset

System -- Process --  pre-data 

System -- Validation -- initial energy

System -- Validation -- initial available

System -- Validation -- energy usable

System -- Validation -- initial autonomy

System -- Validation -- adjusted energy usable

System -- Validation -- adjusted autonomy

System -- Validation -- thermal loss factor

Validation -- ModelAI -- Assist Result

System -- Log

System -- Operator: Go or No Go