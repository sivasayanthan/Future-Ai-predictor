function analyzePrediction() {

    const input = document.getElementById("userInput").value.trim();

    if(input === ""){
        alert("Please enter a statement.");
        return;
    }

    const probability = Math.floor(Math.random() * 41) + 60;

    document.getElementById("progress").style.width = probability + "%";
    document.getElementById("percentage").innerHTML = probability + "%";

    let analysis = "";
    let suggestions = "";

    if(probability >= 85){

        analysis = "This goal looks highly achievable if you remain consistent and continue improving your skills.";

        suggestions =
        "✅ Stay disciplined.<br>" +
        "✅ Keep learning every day.<br>" +
        "✅ Track your progress.<br>" +
        "✅ Never give up.";

    }

    else if(probability >= 70){

        analysis = "Your goal has a good chance of success, but it will require continuous effort and proper planning.";

        suggestions =
        "✅ Improve your skills.<br>" +
        "✅ Practice consistently.<br>" +
        "✅ Learn from experienced people.<br>" +
        "✅ Stay motivated.";

    }

    else{

        analysis = "This goal may be difficult right now, but with better preparation and dedication your chances can improve.";

        suggestions =
        "✅ Build a stronger plan.<br>" +
        "✅ Learn new skills.<br>" +
        "✅ Work on your weaknesses.<br>" +
        "✅ Keep trying.";

    }

    document.getElementById("analysis").innerHTML = analysis;

    document.getElementById("suggestions").innerHTML =
    "<h3>AI Suggestions</h3><br>" + suggestions;

}
