<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Solving Buddy</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f0f8ff;
      padding: 20px;
    }
    .container {
      max-width: 750px;
      margin: auto;
      background: #ffffff;
      padding: 30px;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }
    .title {
      text-align: center;
      font-size: 32px;
      color: #2c3e50;
      margin-bottom: 20px;
    }
    .question {
      font-size: 18px;
      margin-bottom: 25px;
    }
    .option {
      padding: 12px;
      border: 1px solid #ddd;
      border-radius: 6px;
      margin: 10px 0;
      background-color: #f9f9f9;
    }
    .correct {
      background-color: #d4edda;
      border-color: #28a745;
      font-weight: bold;
    }
    .solution {
      background-color: #fffbe6;
      border-left: 5px solid #ffcc00;
      padding: 20px;
      margin-top: 30px;
      font-size: 16px;
      line-height: 1.6;
    }
    .math {
      font-family: 'Cambria Math', serif;
    }
  </style>
</head>
<body>
  <div class="container">
    <div class="title">Solving Buddy</div>

    <h2>Question</h2>

    <div class="question math">
      In triangle ABC, if <i>a<sup>2</sup> + b<sup>2</sup> + c<sup>2</sup> − bc − ca − ab = 0</i>, then the value of:<br>
      <i>sin<sup>2</sup>A + sin<sup>2</sup>B + sin<sup>2</sup>C</i> is:
    </div>

    <div class="option correct">A. <span class="math">9/4</span></div>
    <div class="option">B. <span class="math">4/9</span></div>
    <div class="option">C. <span class="math">(3√3)/2</span></div>
    <div class="option">D. <span class="math">3/2</span></div>

    <div class="solution">
      <strong>Solution:</strong><br><br>

      We are given that:<br>
      <span class="math"><i>a² + b² + c² − bc − ca − ab = 0</i></span><br><br>

      This expression matches a known identity in triangle geometry which holds **only when the triangle is equilateral**.<br><br>

      In an <strong>equilateral triangle</strong>, all sides are equal and all angles are equal to 60°.<br><br>

      So, we know:
      <ul>
        <li>∠A = ∠B = ∠C = 60°</li>
        <li>sin²A + sin²B + sin²C = 3 × sin²(60°)</li>
      </ul>

      We now calculate:<br>
      <span class="math">sin(60°) = √3 / 2</span><br>
      So, <span class="math">sin²(60°) = (√3 / 2)² = 3 / 4</span><br><br>

      Therefore:
      <span class="math">
        sin²A + sin²B + sin²C = 3 × (3/4) = 9/4
      </span><br><br>

      ✅ <strong>Final Answer: 9/4</strong>
    </div>
  </div>
</body>
</html>
