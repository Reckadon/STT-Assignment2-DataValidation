# STT-Assignment2-DataValidation
Learning about modern data validation techniques using Pandera and Great Expectations frameworks through hands-on experience with real-world fitness data. Implementing various validation rules, from basic data type checking to complex cross-column validations.

---
### Features to Implement
1. **Pandera Validation Rules**:
   - Validate the datatype of each column.
   - Analyze each feature and write an appropriate check/scheme for them. _For example, for “rideable_type” check the unique options and ensure that no other entry passes the check._
   - Add data validation rules to verify that a ride's end time occurs after its start time using Pandera's decorator functionality.
2. **Great Expectations Suite**:
   - Validate the datatype of each column by creating an expectation suite.
   - Implement an Action that will send a mail when encountering a failure. Take a screenshot of the mail and attach it to the submission file.
3. **Code Quality**:
    - Maintain **clean**, **modular**, and readable code.
    - Provide comments where necessary.