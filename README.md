# PLCBlockMon

PLCBlockMon is a functional block for Siemens S7 controllers implemented in ladder diagram (LAD) programming language using TIA portal platform v14.

Code of the PLCBlockMon is available within the ZIP file of this project.

After downloading and unzipping the project files it is necessary to import the PLCBlockMon in the TIA portal. This can be done by choosing "Library" section in TIA portal and importing the code as "Global Library".

Now, the data logging functional block (FB) aka PLCBlockMon, related database (DB) and data type can be dragged into the programming area of the TIA project. The PLCBlockMon can then be further dropped into the main (organizational block) programming logic.

The code has been developed on the CPU 1212C with the firmware version v4.2. The functional block requires to be augmented with additional logic for handling log openning, creating, writing, closing and cleaning. More information is available in the research paper "PLCBlockMon: Data Logging and Extraction on PLCs for Cyber Intrusion Detection" published at 5th International Symposium for ICS & SCADA Cyber Security Research 2018 (ICS-CSR).
