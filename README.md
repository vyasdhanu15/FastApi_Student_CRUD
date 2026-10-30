FastAPI Student CRUD ApplicationA lightweight, high-performance RESTful API built with FastAPI and Python for performing Create, Read, Update, and Delete (CRUD) operations on student records.FeaturesFast and Modern: Built on FastAPI, leveraging standard Python type hints for automatic data validation, serialization, and interactive documentation.Full CRUD Support:Create: Add new student profiles.Read: Retrieve individual student details or list all students.Update: Modify existing student information.Delete: Remove student records from the system.Interactive API Docs: Out-of-the-box Swagger UI (/docs) and ReDoc (/redoc) integration.Tech StackFramework: FastAPIServer: UvicornData Validation: PydanticLanguage: Python 3.8+Project StructureFastApi_Student_CRUD/
│
├── main.py          # Application entry point and route handlers
├── models.py        # Pydantic models / Data schemas
├── requirements.txt # Project dependencies
└── README.md        # Project documentation
Getting StartedFollow these instructions to set up and run the project locally on your machine.PrerequisitesEnsure you have Python (version 3.8 or higher) installed on your system.InstallationClone the repository:git clone https://github.com/vyasdhanu15/FastApi_Student_CRUD.git
cd FastApi_Student_CRUD
Create and activate a virtual environment:# On macOS/Linux
python3 -m venv venv
source venv/bin/activate

# On Windows
python -m venv venv
venv\Scripts\activate
Install the dependencies:pip install -r requirements.txt
Running the ApplicationStart the development server using Uvicorn:uvicorn main:app --reload
The API will be available at: http://127.0.0.1:8000Interactive Swagger Documentation: http://127.0.0.1:8000/docsAlternative ReDoc Documentation: http://127.0.0.1:8000/redocAPI Endpoints OverviewMethodEndpointDescriptionGET/studentsRetrieve a list of all studentsPOST/studentsCreate a new student recordGET/students/{student_id}Retrieve a specific student by IDPUT/students/{student_id}Update an existing student recordDELETE/students/{student_id}Delete a student recordContributingContributions, issues, and feature requests are welcome! Feel free to check the issues page.Fork the ProjectCreate your Feature Branch (git checkout -b feature/AmazingFeature)Commit your Changes (git commit -m 'Add some AmazingFeature')Push to the Branch (git push origin feature/AmazingFeature)Open a Pull RequestLicenseDistributed under the MIT License. See LICENSE for more information.
