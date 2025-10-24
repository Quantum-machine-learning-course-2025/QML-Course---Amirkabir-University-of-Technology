<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Quantum Machine Learning – Fall 2025 | Amirkabir University</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', system-ui, -apple-system, sans-serif;
            line-height: 1.6;
            color: #2d3748;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            min-height: 100vh;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 2rem;
        }

        .course-card {
            background: white;
            border-radius: 20px;
            box-shadow: 0 20px 40px rgba(0, 0, 0, 0.1);
            overflow: hidden;
            backdrop-filter: blur(10px);
        }

        .header {
            background: linear-gradient(135deg, #1a202c 0%, #2d3748 100%);
            color: white;
            padding: 3rem 2rem;
            text-align: center;
            position: relative;
        }

        .header::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background: url('data:image/svg+xml,<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 100 100"><defs><pattern id="grid" width="10" height="10" patternUnits="userSpaceOnUse"><path d="M 10 0 L 0 0 0 10" fill="none" stroke="rgba(255,255,255,0.1)" stroke-width="1"/></pattern></defs><rect width="100" height="100" fill="url(%23grid)"/></svg>');
        }

        .course-title {
            font-size: 3rem;
            font-weight: 700;
            margin-bottom: 0.5rem;
            background: linear-gradient(135deg, #81e6d9 0%, #d6bcfa 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            position: relative;
        }

        .university {
            font-size: 1.5rem;
            opacity: 0.9;
            font-weight: 300;
        }

        .content {
            padding: 3rem;
        }

        .section {
            margin-bottom: 3rem;
        }

        .section-title {
            font-size: 1.8rem;
            font-weight: 600;
            color: #2d3748;
            margin-bottom: 1.5rem;
            display: flex;
            align-items: center;
            gap: 0.5rem;
        }

        .welcome-text {
            font-size: 1.2rem;
            line-height: 1.8;
            color: #4a5568;
            margin-bottom: 2rem;
        }

        .info-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
            margin-bottom: 2rem;
        }

        .info-card {
            background: #f7fafc;
            padding: 1.5rem;
            border-radius: 12px;
            border-left: 4px solid #667eea;
        }

        .info-card h3 {
            color: #2d3748;
            margin-bottom: 1rem;
            font-size: 1.1rem;
        }

        .info-card p, .info-card a {
            color: #4a5568;
            text-decoration: none;
        }

        .info-card a:hover {
            color: #667eea;
        }

        .schedule-table {
            width: 100%;
            border-collapse: collapse;
            background: #f7fafc;
            border-radius: 12px;
            overflow: hidden;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.05);
        }

        .schedule-table th,
        .schedule-table td {
            padding: 1rem;
            text-align: left;
            border-bottom: 1px solid #e2e8f0;
        }

        .schedule-table th {
            background: #edf2f7;
            font-weight: 600;
            color: #2d3748;
        }

        .schedule-table tr:hover {
            background: #ebf8ff;
        }

        .links-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 1rem;
        }

        .link-card {
            background: #f7fafc;
            padding: 1.5rem;
            border-radius: 12px;
            text-decoration: none;
            color: inherit;
            transition: all 0.3s ease;
            border: 1px solid #e2e8f0;
        }

        .link-card:hover {
            transform: translateY(-4px);
            box-shadow: 0 12px 20px rgba(0, 0, 0, 0.1);
            border-color: #667eea;
        }

        .link-card h4 {
            display: flex;
            align-items: center;
            gap: 0.5rem;
            margin-bottom: 0.5rem;
            color: #2d3748;
        }

        .contact-section {
            background: linear-gradient(135deg, #edf2f7 0%, #f7fafc 100%);
            padding: 2rem;
            border-radius: 12px;
            text-align: center;
        }

        .footer {
            text-align: center;
            padding: 2rem;
            background: #1a202c;
            color: white;
            margin-top: 3rem;
        }

        @media (max-width: 768px) {
            .container {
                padding: 1rem;
            }
            
            .content {
                padding: 1.5rem;
            }
            
            .course-title {
                font-size: 2rem;
            }
            
            .info-grid {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="course-card">
            <div class="header">
                <h1 class="course-title">Welcome to Quantum Machine Learning</h1>
                <p class="university">Fall 2025 • Amirkabir University of Technology</p>
            </div>

            <div class="content">
                <div class="section">
                    <h2 class="section-title">🧠 What to Expect</h2>
                    <p class="welcome-text">
                        Hello and welcome! This is the central hub for all things related to the <strong>Quantum Machine Learning</strong> 
                        course at <strong>Amirkabir University of Technology</strong> for the Fall 2025 semester. 
                        We're excited to embark on this journey with you!
                    </p>
                    
                    <div class="info-grid">
                        <div class="info-card">
                            <h3>👨‍🏫 Course Team</h3>
                            <p><strong>Instructor:</strong> Dr. Negar Ashari Astani</p>
                            <p><strong>Teaching Assistants:</strong> Nima Yadollahi & Alireza Khalaji</p>
                        </div>
                        
                        <div class="info-card">
                            <h3>📧 Contact & Details</h3>
                            <p><strong>Email:</strong> <a href="mailto:qml.ta2025@gmail.com">qml.ta2025@gmail.com</a></p>
                            <p><strong>Level:</strong> Graduate</p>
                            <p><strong>Duration:</strong> 90 minutes per session</p>
                        </div>
                        
                        <div class="info-card">
                            <h3>📚 Main Textbook</h3>
                            <p><em>Machine Learning with Quantum Computers</em> — Maria Schuld & Francesco Petruccione</p>
                            <a href="http://103.203.175.90:81/fdScript/RootOfEBooks/E%20Book%20collection%20-%202025%20-%20F/AI%20and%20DS/Francesco_Petruccione,_Maria_Schuld_Machine_Learning_with_Quantum.pdf" target="_blank">
                                Download Reference Book (PDF)
                            </a>
                        </div>
                    </div>
                </div>

                <div class="section">
                    <h2 class="section-title">⚙️ Getting Ready</h2>
                    <div class="info-card">
                        <p>To hit the ground running, it would be great if you have some familiarity with:</p>
                        <ul style="margin: 1rem 0; padding-left: 1.5rem;">
                            <li><strong>Python Programming</strong></li>
                            <li><strong>The fundamentals of Quantum Computing</strong></li>
                        </ul>
                        <p><strong>Recommended reading materials:</strong></p>
                        <ul style="padding-left: 1.5rem;">
                            <li>
                                <a href="https://www.thomaswong.net/introduction-to-classical-and-quantum-computing-1e4p.pdf" target="_blank">
                                    Introduction to Classical and Quantum Computing – Thomas Wong
                                </a>
                            </li>
                            <li>
                                <a href="https://profmcruz.wordpress.com/wp-content/uploads/2017/08/quantum-computation-and-quantum-information-nielsen-chuang.pdf" target="_blank">
                                    Quantum Computation and Quantum Information – Nielsen & Chuang
                                </a>
                            </li>
                        </ul>
                    </div>
                </div>

                <div class="section">
                    <h2 class="section-title">🧩 Your TA Session Plan</h2>
                    <p class="welcome-text" style="margin-bottom: 2rem;">
                        Your Teaching Assistants, Nima and Alireza, will be leading these hands-on sessions to help solidify the course concepts. 
                        Each session is a mix of theory and practical coding.
                    </p>
                    
                    <table class="schedule-table">
                        <thead>
                            <tr>
                                <th>#</th>
                                <th>Topic</th>
                                <th>Delivery Mode</th>
                                <th>TA</th>
                            </tr>
                        </thead>
                        <tbody>
                            <tr>
                                <td>1</td>
                                <td>Preprocessing & Data Preparation, Regression (Linear Models)</td>
                                <td>Lesson & Coding</td>
                                <td>Nima</td>
                            </tr>
                            <tr>
                                <td>2</td>
                                <td>Decision Tree, Random Forests (Tree-based Models)</td>
                                <td>Lesson & Coding</td>
                                <td>Alireza</td>
                            </tr>
                            <tr>
                                <td>3</td>
                                <td>Multilayer Perceptron, RNN (Artificial NN)</td>
                                <td>Lesson & Coding</td>
                                <td>Nima</td>
                            </tr>
                            <tr>
                                <td>4</td>
                                <td>Convolutional Neural Network (Artificial NN)</td>
                                <td>Lesson & Coding</td>
                                <td>Alireza</td>
                            </tr>
                            <tr>
                                <td>5</td>
                                <td>Recurrent neural network (Artificial NN)</td>
                                <td>Lesson & Coding</td>
                                <td>Nima</td>
                            </tr>
                            <tr>
                                <td>6</td>
                                <td>SVM (Kernel Method)</td>
                                <td>Lesson & Coding</td>
                                <td>Nima</td>
                            </tr>
                            <tr>
                                <td>7</td>
                                <td>K-Nearest Neighbour (Kernel Method)</td>
                                <td>Lesson & Coding</td>
                                <td>Alireza</td>
                            </tr>
                            <tr>
                                <td>8</td>
                                <td>Boltzmann Machine & RBM (Artificial NN)</td>
                                <td>Lesson & Coding</td>
                                <td>Nima</td>
                            </tr>
                            <tr>
                                <td>9</td>
                                <td>Hopfield Model, Bayesian Network (Graphical Model)</td>
                                <td>Lesson & Coding</td>
                                <td>Alireza</td>
                            </tr>
                        </tbody>
                    </table>
                </div>

                <div class="section">
                    <h2 class="section-title">💻 Helpful Links</h2>
                    <div class="links-grid">
                        <a href="https://classroom.github.com/classrooms/231667307-quantum-machine-learning-course-2025" class="link-card" target="_blank">
                            <h4>🎓 GitHub Classroom</h4>
                            <p>Submit your assignments and projects here</p>
                        </a>
                        <a href="https://github.com/Quantum-machine-learning-course-2025/QML-Course---Amirkabir-University-of-Technology" class="link-card" target="_blank">
                            <h4>📘 Course Repository</h4>
                            <p>Find all course materials and resources</p>
                        </a>
                        <a href="https://youtube.com/playlist?list=PL529eKJTemlBZqi900uIeohSd7qqUEG9U&si=Xq-taFyx1A-p0yDL" class="link-card" target="_blank">
                            <h4>▶️ YouTube Lectures</h4>
                            <p>Watch recorded lectures and tutorials</p>
                        </a>
                    </div>
                </div>

                <div class="section">
                    <div class="contact-section">
                        <h2 class="section-title" style="justify-content: center;">📞 We're Here to Help</h2>
                        <p style="font-size: 1.1rem; margin-bottom: 1rem;">
                            If you have any questions or run into trouble, please don't hesitate to get in touch!
                        </p>
                        <p style="margin-bottom: 1rem;">
                            <strong>📧 Email:</strong> 
                            <a href="mailto:qml.ta2025@gmail.com" style="color: #667eea;">qml.ta2025@gmail.com</a>
                        </p>
                        <p>
                            <strong>🌐 Course Website:</strong> 
                            <a href="https://qucal.aut.ac.ir/" style="color: #667eea;">https://qucal.aut.ac.ir/</a>
                        </p>
                    </div>
                </div>
            </div>

            <div class="footer">
                <p><strong>© 2025 Amirkabir University of Technology</strong></p>
                <p>Department of Physics – Quantum Machine Learning Course</p>
            </div>
        </div>
    </div>
</body>
</html>
