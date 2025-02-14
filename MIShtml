<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MIS Service Ticket</title>
    <link rel="stylesheet" href="styles.css">
</head>

<body>
    <div class="form-container">
        <img src="sti-logo.png" alt="STI College Logo" class="logo">

        <div class="wrapper">
            <h2 class="form-title">MIS Service Ticket</h2>
            <p class="form-subtitle">Please provide the details of the problem</p>
            <form id="service-ticket-form">
                <div class="form-group name-group">
                    <label for="first-name">Name</label>
                    <div class="name-fields">
                        <input type="text" id="first-name" placeholder="First Name" required>
                        <input type="text" id="middle-initial" placeholder="M.I." maxlength="2">
                        <input type="text" id="last-name" placeholder="Last Name" required>
                    </div>
                </div>
                <div class="form-group">
                    <label for="id">Student Number / Employee ID</label>
                    <div class="id-section-group">
                        <input type="text" id="id" placeholder="ID Number" required>
                        <input type="text" id="section" placeholder="Section (for students)" required>
                    </div>
                </div>

                <div class="form-group">
                    <label for="role">Faculty or Student</label>
                    <select id="role" required>
                        <option value="">Select</option>
                        <option value="Faculty">Faculty</option>
                        <option value="Student">Student</option>
                    </select>
                </div>
                <div class="form-group">
                    <label for="category">Issue Category</label>
                    <select id="category" required>
                        <option value="">Select</option>
                        <option value="Facility">Facility</option>
                        <option value="eLMS">Electronic Learning Management System</option>
                    </select>
                </div>
                <div class="form-group">
                    <label for="campus">Campus and Computer ID</label>
                    <div class="campus-computer-group">
                        <input type="text" id="campus" placeholder="STI College campus branch" required>
                        <input type="text" id="computer-id" placeholder="Computer ID / Number" required>
                    </div>
                </div>

                <div class="form-group">
                    <label for="description">Detailed Issue Description</label>
                    <textarea id="description" rows="4" required></textarea>
                </div>
                <div class="form-group upload-container">
                    <label>Upload a File</label>
                    <label for="file-upload" class="upload-btn">Choose a File</label>
                    <input type="file" id="file-upload">
                    <span id="file-name">No file chosen</span>
                </div>
                <button type="submit" class="submit-btn">Submit</button>
            </form>
        </div>

        <div id="success-message" class="hidden">
            <p>Your request has been sent! We guarantee that your problem will be fixed within 24 hours.</p>
            <button onclick="closeMessage()">OK</button>
        </div>
    </div>

    <script src="script.js"></script>
</body>

</html>
