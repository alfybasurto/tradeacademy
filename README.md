<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Career Fit Survey - Maui Trades Academy</title>
</head>
<body class="bg-gray-100 p-6 font-sans">
  <div class="max-w-3xl mx-auto bg-white rounded-2xl shadow-md p-6">
    <h1 class="text-2xl font-bold mb-4 text-center">Maui Trades Academy Career Fit Survey</h1>
    <form action="#" method="POST" class="space-y-4">
      <div>
        <label class="block font-medium">Name</label>
        <input type="text" name="name" class="w-full border p-2 rounded" required>
      </div>
      <div>
        <label class="block font-medium">Email</label>
        <input type="email" name="email" class="w-full border p-2 rounded" required>
      </div>
      <div>
        <label class="block font-medium">Are you over or under 18?</label>
        <select name="age_range" class="w-full border p-2 rounded">
          <option value="under_18">Under 18</option>
          <option value="over_18">Over 18</option>
        </select>
      </div>

      <hr class="my-4">
      <h2 class="text-xl font-semibold">Self-Scored Career Survey</h2>

      <p class="mb-4 text-sm text-gray-600">Rate each statement from 1 (Not at all like me) to 5 (Exactly like me). Tally your scores at the end to see which trade might suit you best!</p>

      <div class="space-y-4">
        <div>
          <label class="block font-medium">1. I enjoy working with tools and building things with my hands.</label>
          <input type="number" name="q1" min="1" max="5" class="w-full border p-2 rounded">
        </div>

        <div>
          <label class="block font-medium">2. I prefer working outdoors and being physically active.</label>
          <input type="number" name="q2" min="1" max="5" class="w-full border p-2 rounded">
        </div>

        <div>
          <label class="block font-medium">3. I like solving technical or mechanical problems.</label>
          <input type="number" name="q3" min="1" max="5" class="w-full border p-2 rounded">
        </div>

        <div>
          <label class="block font-medium">4. I’m detail-oriented and enjoy precision work.</label>
          <input type="number" name="q4" min="1" max="5" class="w-full border p-2 rounded">
        </div>

        <div>
          <label class="block font-medium">5. I enjoy helping people and working in teams.</label>
          <input type="number" name="q5" min="1" max="5" class="w-full border p-2 rounded">
        </div>

        <div>
          <label class="block font-medium">6. I’m interested in electrical or smart home systems.</label>
          <input type="number" name="q6" min="1" max="5" class="w-full border p-2 rounded">
        </div>

        <div>
          <label class="block font-medium">7. I like understanding how engines or mechanical systems work.</label>
          <input type="number" name="q7" min="1" max="5" class="w-full border p-2 rounded">
        </div>

        <div>
          <label class="block font-medium">8. I enjoy working with water systems or understanding how plumbing works.</label>
          <input type="number" name="q8" min="1" max="5" class="w-full border p-2 rounded">
        </div>

        <div>
          <label class="block font-medium">9. I see myself running my own business someday.</label>
          <input type="number" name="q9" min="1" max="5" class="w-full border p-2 rounded">
        </div>

        <div>
          <label class="block font-medium">10. I want a job that makes me feel proud and needed in the community.</label>
          <input type="number" name="q10" min="1" max="5" class="w-full border p-2 rounded">
        </div>
      </div>

      <p class="text-sm mt-6 text-gray-700">Scoring:</p>
      <ul class="text-sm text-gray-700 list-disc list-inside">
        <li>40–50: You’d likely thrive in the trades! Consider plumbing, electrical, HVAC, automotive, or carpentry.</li>
        <li>30–39: You may enjoy some trades with strong mentoring and hands-on practice.</li>
        <li>20–29: Consider exploring creative or support roles within the trades or allied services.</li>
        <li>Below 20: You may prefer careers in education, counseling, or administration that still support trade efforts.</li>
      </ul>

      <div class="text-center pt-6">
        <button type="submit" class="bg-blue-600 text-white px-6 py-2 rounded-xl hover:bg-blue-700">Submit Survey</button>
      </div>
    </form>
  </div>
</body>
</html>
