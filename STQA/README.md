## 𝐒𝐨𝐟𝐭𝐰𝐚𝐫𝐞 𝐓𝐞𝐬𝐭𝐢𝐧𝐠 𝐚𝐧𝐝 𝐐𝐮𝐚𝐥𝐢𝐭𝐲 𝐀𝐬𝐬𝐮𝐫𝐚𝐧𝐜𝐞

> - Unit I  : Introduction to Software Testing
> - Unit II : Test planning and Quality Management


## 𝐔𝐧𝐢𝐭 𝐈: 𝐈𝐧𝐭𝐫𝐨𝐝𝐮𝐜𝐭𝐢𝐨𝐧 𝐭𝐨 𝐒𝐨𝐟𝐭𝐰𝐚𝐫𝐞 𝐓𝐞𝐬𝐭𝐢𝐧𝐠

<div align=center>
  <br>

![image](https://user-images.githubusercontent.com/68887544/193410105-263e9192-c93a-4bc6-b672-d0ae6a3481f9.png)


  <br>
</div>

- Historical perspectives

`^ I don't think it would be that important but will do later if time permits`

- Definition:
> `Software Quality Assurance`
> - SQA is a process which guarantees that all software engineering progressions, methods, activities and work items are examined and comply contradiction of the defined standards.
>
> `Software Quality`
> - Software Quality means how well the software is designed and how well the software conforms to that design.
>

- Core components of Quality:
> - Customer Satisfaction
> - Quality Parameters
>   - Define: Defining product requirements in terms of attributes.
>   - Measure: Measuring quality in quantitative terms.
>   - Monitor: Observing performance of processes used in development, testing, and delivery.
>   - Control: Must have functions like quality control, validation, verification, and quality assurance. Product progress must be reviewed and controlled through these functions.
>   - Improve: Continuous and continual improvement methods should be followed by the organization.
> - Efforts for improvement
> - Continual / Continuous Process Improvement

- Continuous and Continual Improvement difference:

> Continuous Improvement | Continual Improvement
> ---|---
> Continuous Improvement is dynamic in nature | Continual improvement is dynamic and static change in management
> The changes are done at every stage and everytime | The changes are done before taking next step of improvement
> It Continuously strive for excellence | It performs periodic improvement followed by stabilization process.

- Customer, Suppliers and processes:
> - For every organization, there always exists someone who supplies and someone who buys the resources, the one who provides are known as suppliers where the one who is being provided is known as the customer.
> - Suppliers and Customers both maybe inside or outside of the organization.

- Objectives of Testing:
> - The objectives of testing are to:
>   - check if there exists any defects in the software and prevent them.
>   - check if the software passes all the defined test cases it was designed for and validate them.
>   - check if the software meet defined requirements
>   - build confidence among stakeholders and developers that the product is build as it was designed.
>   - identify, analyze and reduce risk
>   - find chances of failure and technological durability of the product.

- Testing and Debugging:
> - Testing:
>   - The process of verifying and validating if the product is bug free and meet all the defined user as well as customer requirements is known as testing.
>
> - Debugging:
>   - The process of identifying, analyzing and removing errors that cause failure is known as debugging.
>   

- Need of testing:
> - There is a need for testing because testing helps us in:
>   - identification, analysis and removal of errors.
>   - checking if the software is adaptable to different test cases and scenarios.
>   - checking if there exists any risk
>   - checking if the project meet the requirement specified beforehand.
>   - making sure if the software is bug free and user friendly.


- Quality Assurance and Testing:
> - Quality Assurance:
>   - The process of making sure if the product is high quality and meets defined quality standards is known as quality assurance.
> - Testing:
>   - The process of verifying and validating the correctness of features and functionalities of the product is known as testing.

- Difference between quality assurance and testing:
> Quality Assurance | Testing
> --- | ---
> Process of making sure if the product meets specified quality requirements | Process of verifying and validating features and functionality for correctness
> It includes each step of software development | It is done at the end of development
> Ensure the quality by checking all the procedures and processes are in place | validate specifications against likely and unlikely inputs
> Focuses on processes to achieve quality | Focuses on actual testing of the final product to make sure if it's working properly
> It's process oriented | It's Product oriented
> It's preventive method | It's corrective method
> Assures quality | Controls quality

- Why software has errors, defects and failures?
> - Because of:
>   - Poor specification of requirements
>   - Complexity of feature required
>   - Logical falsies while writing the code.
>   - Programming errors.
>   - Use of Obsolete libraries and methodologies
>   - Lack of skilled developers.
>   - Badly written and poorly documented code.

- Relationship between errors, defects and failures:
> - An error cause defect which if not removed might cause failure.
> - Error ---(leads to)---> Defect ---(leads to)--->  Failure

- Causes of errors, defects and failure:
> - Developer was pressurized to complete the project within impossible time constraints and not given enough time to think and write efficient code.
> - Human mistakes leading to errors, defects and failure.
> - Inexperienced or insufficiently skilled developer or project contributor.
> - Miscommunication between project participants.
> - Feature way too complex to design and code.
> - Use of new or unfamiliar technological stack.
> - Improper environmental conditions.

- Effects of errors, defects and failures:
> - A lot of errors, defects and failures of software will cause technical debt and the project will not be able to met the specified deadline.
> - Fixing EDF (errors, defects and failures `don't use this short form in exam`) might take a long time.
> - Increase in time might lead to increase in the cost of the product (because developers need to be paid for the time they spend developing the product.)
> - EDF might cause the software to produce unintended or unexpected results.
> - Product might fail to deliver what it was meant to deliver.

- Total Quality Management (TQM):
> - A Management process that make sure all work and process to build the software aims towards the common goal of improving the overall quality or service or the product.
> - It is a continuous process of testing, quality assurance, supply chain management to improve the customer experience.
> - It aims to hold all parties involved in building the product accountable for the overall quality of the final product.
> - TQM is applicable to all aspects of the organization i.e. all business processes.

- Quality Practices of TQM:
> - Continuous improvement process (CIP): The main aim is to continuously work and improve the overall quality of the product at every stage from start to finish.
> - Zero Defects: The product or service  should not have any defects meaning the product should be of the most superior quality.
> - Six Sigma:
>   - TQM follows Six Sigma Method/principle
>   - Six Sigma Method is a method of calculating measurable improvements or defects in a product.
> - PDCA cycle:
>   - TQM follows PDCA cycle.
>   - PDCA stands for plan-do-check-act.


## 𝐔𝐧𝐢𝐭 𝐈𝐈: 𝐓𝐞𝐬𝐭 𝐏𝐥𝐚𝐧𝐧𝐢𝐧𝐠 𝐚𝐧𝐝 𝐐𝐮𝐚𝐥𝐢𝐭𝐲 𝐌𝐚𝐧𝐚𝐠𝐞𝐦𝐞𝐧𝐭

<div align=center>
  <br>

![image](https://user-images.githubusercontent.com/68887544/193410117-ed8de8eb-f507-4b5b-b929-6f4a38658cba.png)  

  <br>
</div>
