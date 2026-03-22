# Dog Facts API v1 Replica — Node.js & Express

## Assignment

**Objective:** Build a simplified version of the Dog Facts API using Node.js and Express.js. This API allows users to retrieve dog facts in JSON format.

---

## Requirements

### Tech Stack
- **Node.js** and **Express.js**

### API Endpoints

#### `GET /facts`
Returns a list of dog facts.

**Query Parameters:**

| Parameter | Type    | Description                                      |
|-----------|---------|--------------------------------------------------|
| `number`  | integer | Number of dog facts to return. If omitted, returns all facts. |

**Example Request:**
```
GET /facts?number=1
```

**Example Response:**
```json
{ "facts": ["A group of pugs is called a grumble."], "success": true }
```

### Expected Functionality
- **Server Setup** — Create an Express.js server that listens on a designated port.
- **Data Storage** — Store dog facts in an array within your server code. The data file (`dog_facts.js`) is provided on Canvas.
- **`GET /facts` Endpoint** — Reads the `number` query parameter. If provided, returns that many facts; otherwise returns all facts.
- **Error Handling** — Implement basic error handling for invalid requests.
- **Documentation** — Write clear API documentation explaining how to use your endpoints.

---

## Submission

### GitHub Repository
- Push your program to a new public GitHub repository.
- Include all source code files and a `README.md` describing the project and how to run it.

### Demonstration
Provide a video demonstrating:
- Program functionality
- Test cases (at least 3 normal cases and at least 3 edge cases)

### Submit
- Link to your GitHub repository
- YouTube link (public or unlisted) to your video demonstration
