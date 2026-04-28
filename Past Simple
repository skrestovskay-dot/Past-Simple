<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=yes">
    <title>Interactive Worksheet: Past Simple Irregular Verbs | Grade 5</title>
    <style>
        * {
            box-sizing: border-box;
        }

        body {
            background: linear-gradient(145deg, #f0f7ff 0%, #e9eef5 100%);
            font-family: 'Segoe UI', Roboto, 'Helvetica Neue', sans-serif;
            margin: 0;
            padding: 20px;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
        }

        .worksheet-container {
            max-width: 1100px;
            width: 100%;
            background-color: white;
            border-radius: 48px;
            box-shadow: 0 25px 45px -12px rgba(0, 0, 0, 0.25);
            overflow: hidden;
            transition: all 0.2s;
        }

        /* header */
        .worksheet-header {
            background: #2c3e66;
            padding: 20px 32px;
            color: white;
        }

        .worksheet-header h1 {
            margin: 0;
            font-size: 1.9rem;
            font-weight: 600;
            letter-spacing: -0.3px;
        }

        .worksheet-header p {
            margin: 8px 0 0;
            opacity: 0.85;
            font-size: 1rem;
        }

        /* content */
        .content {
            padding: 24px 32px 32px;
        }

        /* rule card */
        .rule-box {
            background: #fef7e0;
            border-left: 12px solid #f4b942;
            border-radius: 28px;
            padding: 16px 24px;
            margin-bottom: 40px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.02);
        }

        .rule-box h3 {
            margin: 0 0 8px 0;
            color: #b45f06;
            font-weight: 600;
            font-size: 1.35rem;
        }

        .rule-box p {
            margin: 6px 0;
            font-size: 1rem;
            line-height: 1.4;
            color: #2d2f36;
        }

        .rule-box ul {
            margin: 8px 0 4px 20px;
        }

        .rule-box li {
            margin: 5px 0;
        }

        /* exercise styling */
        .exercise {
            background: #ffffff;
            border-radius: 32px;
            margin-bottom: 48px;
            border: 1px solid #e2e8f0;
            box-shadow: 0 6px 12px -8px rgba(0, 0, 0, 0.05);
            overflow: hidden;
        }

        .exercise-title {
            background: #f8fafc;
            padding: 14px 28px;
            border-bottom: 2px solid #cbd5e1;
        }

        .exercise-title h2 {
            margin: 0;
            font-size: 1.6rem;
            font-weight: 600;
            color: #1e293b;
            display: flex;
            align-items: center;
            gap: 12px;
        }

        .exercise-title h2 span {
            background: #2c3e66;
            color: white;
            font-size: 1rem;
            padding: 4px 12px;
            border-radius: 60px;
        }

        .exercise-body {
            padding: 20px 28px 28px;
        }

        /* verb grid (ex1) */
        .verb-grid {
            display: flex;
            flex-direction: column;
            gap: 12px;
            margin-bottom: 28px;
        }

        .verb-row {
            display: flex;
            align-items: center;
            flex-wrap: wrap;
            gap: 12px;
            background: #f9f9ff;
            padding: 10px 16px;
            border-radius: 60px;
            border: 1px solid #e2edff;
        }

        .verb-base {
            font-weight: 700;
            font-size: 1.25rem;
            width: 100px;
            color: #0f2b3d;
        }

        .verb-input {
            flex: 2;
            min-width: 160px;
        }

        .verb-input input {
            width: 100%;
            padding: 12px 16px;
            font-size: 1rem;
            border: 2px solid #cbd5e1;
            border-radius: 48px;
            transition: 0.2s;
            font-family: monospace;
            background: white;
        }

        .verb-input input:focus {
            border-color: #2c3e66;
            outline: none;
            box-shadow: 0 0 0 3px rgba(44, 62, 102, 0.2);
        }

        .feedback-icon {
            width: 40px;
            text-align: center;
            font-size: 1.5rem;
        }

        /* sentences area */
        .sentences-list {
            display: flex;
            flex-direction: column;
            gap: 20px;
            margin: 20px 0 28px;
        }

        .sentence-item {
            background: #ffffff;
            border: 1px solid #e9edf2;
            border-radius: 28px;
            padding: 12px 20px;
            transition: 0.1s;
        }

        .sentence-text {
            font-size: 1.08rem;
            margin-bottom: 12px;
            color: #1e293b;
            font-weight: 500;
            line-height: 1.4;
        }

        .blank-input {
            display: inline-block;
            min-width: 130px;
        }

        .blank-input input {
            padding: 8px 12px;
            font-size: 0.95rem;
            border: 2px solid #cbd5e1;
            border-radius: 40px;
            width: 150px;
            text-align: center;
            font-family: monospace;
            font-weight: 500;
        }

        .sentence-feedback {
            margin-top: 8px;
            font-size: 0.85rem;
            padding-left: 8px;
            min-height: 28px;
            color: #2d3748;
        }

        /* buttons */
        .button-group {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-between;
            align-items: center;
            gap: 15px;
            margin-top: 10px;
        }

        .btn {
            border: none;
            background: #eef2ff;
            padding: 10px 22px;
            border-radius: 40px;
            font-weight: 600;
            font-size: 0.9rem;
            cursor: pointer;
            transition: 0.2s;
            font-family: inherit;
        }

        .btn-primary {
            background: #2c3e66;
            color: white;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }

        .btn-primary:hover {
            background: #1e2b4a;
            transform: scale(0.97);
        }

        .btn-secondary {
            background: #e2e8f0;
            color: #1e293b;
        }

        .btn-secondary:hover {
            background: #cbd5e1;
        }

        .score-area {
            background: #eef2ff;
            border-radius: 32px;
            padding: 12px 24px;
            text-align: center;
            font-weight: bold;
            font-size: 1.1rem;
            margin-top: 20px;
        }

        .correct {
            color: #15803d;
            border-color: #86efac;
        }

        .incorrect {
            color: #b91c1c;
        }

        footer {
            background: #f1f5f9;
            text-align: center;
            font-size: 0.75rem;
            padding: 14px;
            color: #475569;
            border-top: 1px solid #e2e8f0;
        }

        @media (max-width: 650px) {
            .content {
                padding: 20px;
            }
            .verb-row {
                border-radius: 24px;
            }
            .verb-base {
                width: 80px;
                font-size: 1rem;
            }
        }
    </style>
</head>
<body>
<div class="worksheet-container">
    <div class="worksheet-header">
        <h1>📘 Past Simple: Irregular Verbs</h1>
        <p>Grade 5 | Interactive Worksheet | Practice & Check</p>
    </div>
    <div class="content">
        <!-- RULE SECTION: how verbs change -->
        <div class="rule-box">
            <h3>📖 Grammar Rule: Past Simple (Irregular Verbs)</h3>
            <p>Unlike regular verbs (add -ed), <strong>irregular verbs</strong> change their form in the past simple. 
            There are different groups:</p>
            <ul>
                <li><strong>🔁 Group 1 – one vowel changes:</strong> <em>swim → swam, sing → sang, drive → drove, write → wrote</em></li>
                <li><strong>🔄 Group 2 – different word completely:</strong> <em>go → went, feel → felt, sleep → slept, build → built</em></li>
                <li><strong>🧠 Group 3 – all three forms are different:</strong> <em>know → knew, grow → grew</em></li>
                <li><strong>✏️ Important:</strong> Some stay the same? No, all these verbs are irregular and change!</li>
            </ul>
            <p>⭐ Remember: second form = Past Simple (V2). Use it for past actions (yesterday, last week, in 2010).</p>
        </div>

        <!-- EXERCISE 1: 10 verbs -> write past form -->
        <div class="exercise">
            <div class="exercise-title">
                <h2>✏️ Exercise 1 <span>10 points</span></h2>
                <p style="margin: 5px 0 0 0; color: #475569;">Write the <strong>past simple form (second form)</strong> of each verb.</p>
            </div>
            <div class="exercise-body">
                <div class="verb-grid" id="verbGrid">
                    <!-- verbs list will be populated by js but static fallback -->
                </div>
                <div class="button-group">
                    <button class="btn btn-primary" id="checkEx1Btn">✅ Check Exercise 1</button>
                    <button class="btn btn-secondary" id="resetEx1Btn">⟳ Clear answers</button>
                </div>
                <div id="ex1Score" class="score-area" style="margin-top: 20px;">✨ Not checked yet</div>
            </div>
        </div>

        <!-- EXERCISE 2: sentences with gaps (verbs from ex1) -->
        <div class="exercise">
            <div class="exercise-title">
                <h2>📝 Exercise 2 <span>10 sentences</span></h2>
                <p>Complete each sentence with the <strong>past simple form</strong> of a verb from Exercise 1.</p>
            </div>
            <div class="exercise-body">
                <div class="sentences-list" id="sentencesContainer"></div>
                <div class="button-group">
                    <button class="btn btn-primary" id="checkEx2Btn">🔍 Check Exercise 2</button>
                    <button class="btn btn-secondary" id="resetEx2Btn">⟳ Clear all sentences</button>
                </div>
                <div id="ex2Score" class="score-area" style="margin-top: 20px;">📌 Not checked yet</div>
            </div>
        </div>
    </div>
    <footer>
        🌟 Interactive worksheet | Past simple irregular verbs | Grade 5 (RB)
    </footer>
</div>

<script>
    // ----- DATA -----
    // base verbs and their correct past forms (second form)
    const verbsData = [
        { base: "swim", past: "swam" },
        { base: "drive", past: "drove" },
        { base: "sleep", past: "slept" },
        { base: "sing", past: "sang" },
        { base: "go", past: "went" },
        { base: "know", past: "knew" },
        { base: "feel", past: "felt" },
        { base: "write", past: "wrote" },
        { base: "build", past: "built" },
        { base: "grow", past: "grew" }
    ];

    // sentences for exercise 2: each object contains sentence text with a placeholder ___ and the correct verb (base -> paste past)
    // we will use the base verb to map the correct past form from verbsData.
    const sentencesData = [
        { text: "Yesterday, I ________ (swim) in the lake for an hour.", baseVerb: "swim" },
        { text: "Dad ________ (drive) us to the museum last Sunday.", baseVerb: "drive" },
        { text: "The baby ________ (sleep) peacefully through the whole night.", baseVerb: "sleep" },
        { text: "She ________ (sing) a beautiful song at the school concert.", baseVerb: "sing" },
        { text: "We ________ (go) to the amusement park two days ago.", baseVerb: "go" },
        { text: "I ________ (know) the answer to that difficult question.", baseVerb: "know" },
        { text: "After the long walk, he ________ (feel) very tired.", baseVerb: "feel" },
        { text: "Tom ________ (write) a funny story for the class project.", baseVerb: "write" },
        { text: "Workers ________ (build) a new playground near our school last summer.", baseVerb: "build" },
        { text: "The flowers ________ (grow) very fast in the warm weather.", baseVerb: "grow" }
    ];

    // helper: get past form from base
    function getPastFromBase(baseWord) {
        const found = verbsData.find(v => v.base === baseWord);
        return found ? found.past : "";
    }

    // ----- EXERCISE 1 Rendering & Logic -----
    let ex1Inputs = []; // store references

    function renderExercise1() {
        const grid = document.getElementById("verbGrid");
        grid.innerHTML = "";
        ex1Inputs = [];
        verbsData.forEach((verb, idx) => {
            const row = document.createElement("div");
            row.className = "verb-row";
            row.setAttribute("data-index", idx);
            const baseSpan = document.createElement("div");
            baseSpan.className = "verb-base";
            baseSpan.textContent = verb.base;
            const inputDiv = document.createElement("div");
            inputDiv.className = "verb-input";
            const input = document.createElement("input");
            input.type = "text";
            input.placeholder = "past form...";
            input.autocomplete = "off";
            input.id = `verbInput_${idx}`;
            const feedbackSpan = document.createElement("div");
            feedbackSpan.className = "feedback-icon";
            feedbackSpan.id = `fbIcon_${idx}`;
            feedbackSpan.textContent = "⚪";
            inputDiv.appendChild(input);
            row.appendChild(baseSpan);
            row.appendChild(inputDiv);
            row.appendChild(feedbackSpan);
            grid.appendChild(row);
            ex1Inputs.push(input);
        });
    }

    function checkExercise1() {
        let correctCount = 0;
        for (let i = 0; i < verbsData.length; i++) {
            const userAnswer = ex1Inputs[i].value.trim().toLowerCase();
            const correctPast = verbsData[i].past;
            const feedbackSpan = document.getElementById(`fbIcon_${i}`);
            const inputField = ex1Inputs[i];
            if (userAnswer === correctPast) {
                correctCount++;
                feedbackSpan.innerHTML = "✅";
                feedbackSpan.style.color = "#15803d";
                inputField.style.borderColor = "#86efac";
                inputField.style.backgroundColor = "#f0fdf4";
            } else {
                feedbackSpan.innerHTML = "❌";
                feedbackSpan.style.color = "#b91c1c";
                inputField.style.borderColor = "#fecaca";
                inputField.style.backgroundColor = "#fff5f5";
            }
        }
        const scoreDiv = document.getElementById("ex1Score");
        scoreDiv.innerHTML = `🎯 Your score: ${correctCount} / ${verbsData.length} correct. ${correctCount === verbsData.length ? "Perfect! Great job! 🌟" : "Check the wrong ones and try again!"}`;
        if (correctCount === verbsData.length) {
            scoreDiv.style.background = "#dff9e6";
        } else {
            scoreDiv.style.background = "#eef2ff";
        }
    }

    function resetExercise1() {
        for (let i = 0; i < ex1Inputs.length; i++) {
            ex1Inputs[i].value = "";
            ex1Inputs[i].style.borderColor = "#cbd5e1";
            ex1Inputs[i].style.backgroundColor = "white";
            const fbSpan = document.getElementById(`fbIcon_${i}`);
            if (fbSpan) {
                fbSpan.innerHTML = "⚪";
                fbSpan.style.color = "initial";
            }
        }
        document.getElementById("ex1Score").innerHTML = "✨ Not checked yet";
        document.getElementById("ex1Score").style.background = "#eef2ff";
    }

    // ----- EXERCISE 2 Rendering & Logic -----
    let sentenceInputs = [];  // store input references per sentence

    function renderExercise2() {
        const container = document.getElementById("sentencesContainer");
        container.innerHTML = "";
        sentenceInputs = [];
        sentencesData.forEach((sentence, idx) => {
            const sentDiv = document.createElement("div");
            sentDiv.className = "sentence-item";
            sentDiv.dataset.index = idx;
            // prepare text with blank placeholder as input
            // we replace the (verb) part: but better: display sentence with [_______]
            let displayText = sentence.text;
            // we will insert an input field instead of the original blank placeholder.
            // we'll extract the part before parentheses? easier: render sentence text but with inline input.
            // e.g. "Yesterday, I ________ (swim) in the lake." - replace the blank.
            // we replace the pattern "________" with dynamic input.
            let sentenceWithoutMarker = sentence.text.replace(/________/g, '______');
            const textBeforeInput = sentenceWithoutMarker.substring(0, sentenceWithoutMarker.indexOf('______'));
            const textAfterInput = sentenceWithoutMarker.substring(sentenceWithoutMarker.indexOf('______') + 6);
            // create paragraph structure
            const sentencePara = document.createElement("div");
            sentencePara.className = "sentence-text";
            const leftSpan = document.createElement("span");
            leftSpan.textContent = textBeforeInput;
            const inputField = document.createElement("input");
            inputField.type = "text";
            inputField.placeholder = "past verb";
            inputField.id = `sentInput_${idx}`;
            inputField.style.width = "130px";
            inputField.style.margin = "0 4px";
            inputField.autocomplete = "off";
            const rightSpan = document.createElement("span");
            rightSpan.textContent = textAfterInput;
            sentencePara.appendChild(leftSpan);
            sentencePara.appendChild(inputField);
            sentencePara.appendChild(rightSpan);
            // feedback line
            const feedbackDiv = document.createElement("div");
            feedbackDiv.className = "sentence-feedback";
            feedbackDiv.id = `sentFb_${idx}`;
            sentDiv.appendChild(sentencePara);
            sentDiv.appendChild(feedbackDiv);
            container.appendChild(sentDiv);
            sentenceInputs.push(inputField);
        });
    }

    function checkExercise2() {
        let correctSentences = 0;
        for (let i = 0; i < sentencesData.length; i++) {
            const userAnswer = sentenceInputs[i].value.trim().toLowerCase();
            const correctPast = getPastFromBase(sentencesData[i].baseVerb);
            const feedbackDiv = document.getElementById(`sentFb_${i}`);
            const inputElem = sentenceInputs[i];
            if (userAnswer === correctPast) {
                correctSentences++;
                feedbackDiv.innerHTML = "✅ Correct! Well done.";
                feedbackDiv.style.color = "#15803d";
                inputElem.style.borderColor = "#86efac";
                inputElem.style.backgroundColor = "#f0fdf4";
            } else {
                feedbackDiv.innerHTML = `❌ Not quite. The correct past form of "${sentencesData[i].baseVerb}" is "${correctPast}".`;
                feedbackDiv.style.color = "#b91c1c";
                inputElem.style.borderColor = "#fecaca";
                inputElem.style.backgroundColor = "#fff5f5";
            }
        }
        const scoreDiv = document.getElementById("ex2Score");
        scoreDiv.innerHTML = `📊 Your result: ${correctSentences} / ${sentencesData.length} correct. ${correctSentences === sentencesData.length ? "Excellent! You know the past forms! 🎉" : "Review the past forms and try again."}`;
        if (correctSentences === sentencesData.length) {
            scoreDiv.style.background = "#dff9e6";
        } else {
            scoreDiv.style.background = "#eef2ff";
        }
    }

    function resetExercise2() {
        for (let i = 0; i < sentenceInputs.length; i++) {
            if (sentenceInputs[i]) {
                sentenceInputs[i].value = "";
                sentenceInputs[i].style.borderColor = "#cbd5e1";
                sentenceInputs[i].style.backgroundColor = "white";
            }
            const fbDiv = document.getElementById(`sentFb_${i}`);
            if (fbDiv) {
                fbDiv.innerHTML = "";
                fbDiv.style.color = "#2d3748";
            }
        }
        document.getElementById("ex2Score").innerHTML = "📌 Not checked yet";
        document.getElementById("ex2Score").style.background = "#eef2ff";
    }

    // initial render
    renderExercise1();
    renderExercise2();

    // attach events
    document.getElementById("checkEx1Btn").addEventListener("click", checkExercise1);
    document.getElementById("resetEx1Btn").addEventListener("click", resetExercise1);
    document.getElementById("checkEx2Btn").addEventListener("click", checkExercise2);
    document.getElementById("resetEx2Btn").addEventListener("click", resetExercise2);

    // optional: allow Enter key check for easy use but not necessary, but nice:
    function handleEnterOnInputs(inputsArray, checkFunction) {
        inputsArray.forEach(input => {
            if (input) {
                input.addEventListener("keypress", (e) => {
                    if (e.key === "Enter") {
                        e.preventDefault();
                        checkFunction();
                    }
                });
            }
        });
    }
    // after render dynamic, but we can re-apply after renders but they exist.
    setTimeout(() => {
        if (ex1Inputs.length) handleEnterOnInputs(ex1Inputs, checkExercise1);
        if (sentenceInputs.length) handleEnterOnInputs(sentenceInputs, checkExercise2);
    }, 100);
    // also observe dynamic new sentences from renderExercise2 already set, but safe:
    const observer = new MutationObserver(() => {
        if (ex1Inputs.length) handleEnterOnInputs(ex1Inputs, checkExercise1);
        if (sentenceInputs.length) handleEnterOnInputs(sentenceInputs, checkExercise2);
    });
    observer.observe(document.getElementById("sentencesContainer"), { childList: true, subtree: true });
</script>
</body>
</html>
