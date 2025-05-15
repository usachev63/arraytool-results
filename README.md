# Array Tool Evaluation

Evaluation of the automatic array finding tool for C programs on open source codebases.

## DMM

DMM open source project by Huawei (https://github.com/Huawei/DMM) --- a network software framework. This project closely resembles the codebase, for which the tool was designed.

| functions | arrays (manual) | arrays (tool) | tool precision | tool recall   | correct length |
|-----------|-----------------|---------------|----------------|---------------|----------------|
| 77        | 567             | 704           | **79%** (554/704)  | **98%** (554/567) | **69%** (380/554)  |
