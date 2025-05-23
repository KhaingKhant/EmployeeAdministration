# IRISMoreTraining: ^MKEN2AUNG & LoadData

This project demonstrates ObjectScript programming and data handling in InterSystems IRIS, focusing on permissions, employee, and group data. It is designed for training and practice using only the following files:

- **^MKEN2AUNG.mac**: Contains exercises (A1–A17) for querying, updating, and displaying permission and employee data. Uses the `^MKEN1AUNG`, `^MKEN2AUNG`, and `^MSYA` globals for its operations.
- **LoadData.mac**: Loads sample data into the globals required for the exercises. Also creates backup/variant globals: `^MKEN1AUNG`, `^MKEN2AUNG`.

## Usage

1. **Load Sample Data**
   - Run the `LoadData` routine to populate the globals:
     ```
     Do ^LoadData
     ```

2. **Run Exercises**
   - Call any exercise in `^MKEN2AUNG.mac` as needed. For example:
     ```
     Do A1^^MKEN2AUNG
     Do A15^^MKEN2AUNG
     ```


