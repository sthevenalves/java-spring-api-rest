<h1>API Restfull</h1>

 ![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
 ![Spring](https://img.shields.io/badge/Spring-6DB33F.svg?style=for-the-badge&logo=Spring&logoColor=white)
 [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

<p>This project is a Rest API built using Java, Java Spring, localStorage as a database</p>

<h2>Table of Contents</h2>
<ul>
  <li>Installation</li>
  <li>Usage
  <li>API Endpoints</li>
  <li>Database</li>
</ul>
<h2>Installation</h2>
<p>
  <ol>
    <li>Clone the repository:</li>
    
    git clone https://github.com/sthevenalves/java-spring-crud.git](https://github.com/sthevenalves/java-spring-api-rest.git
    
   <li>Install dependencies with Maven</li>
  </ol>
</p>
<h2>Usage</h2>
<p>
  <ol>
    <li>Start the application with Maven</li>
    <li>The API will be accessible at http://localhost:8080/</li>
  </ol>
</p>
  <h2>API Endpoints</h2>
  <p>
    The API provides the following endpoints:
    
  GET / - Retrieve a list of all data.

      [
        {
            "id": 1,
            "name": "Teclado Membrana",
            "price": 116.0,
            "departament": {
                "id": 1,
                "name": "Tech"
            }
        },
        {
            "id": 2,
            "name": "PC Gamer",
            "price": 4200.0,
            "departament": {
                "id": 1,
                "name": "Tech"
            }
        },
        {
            "id": 3,
            "name": "Ração Gato",
            "price": 56.0,
            "departament": {
                "id": 2,
                "name": "Pet"
            }
        }
    ]
    
  </p>

  <h2>Database</h2>
  <p>
  The project utilizes LocalStorage as the database.
  </p>

