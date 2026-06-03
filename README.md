<!DOCTYPE html><html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Smart Digital Prescription</title>
<style>
    *{
        margin:0;
        padding:0;
        box-sizing:border-box;
        font-family:Arial, sans-serif;
    }body{
    background:#f4f7fc;
    padding:30px;
}

.container{
    max-width:900px;
    margin:auto;
    background:#fff;
    border-radius:15px;
    padding:30px;
    box-shadow:0 5px 20px rgba(0,0,0,0.1);
}

.header{
    text-align:center;
    margin-bottom:30px;
}

.header h1{
    color:#1e88e5;
    margin-bottom:10px;
}

.patient-info{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:15px;
    margin-bottom:25px;
}

.card{
    background:#f8fbff;
    padding:15px;
    border-left:5px solid #1e88e5;
    border-radius:8px;
}

.section-title{
    color:#1e88e5;
    margin:20px 0 15px;
}

.medicine{
    background:#fafafa;
    border-radius:10px;
    padding:18px;
    margin-bottom:15px;
    border:1px solid #ddd;
}

.medicine h3{
    color:#333;
    margin-bottom:10px;
}

ul{
    padding-left:20px;
}

.footer{
    text-align:center;
    margin-top:25px;
    padding-top:20px;
    border-top:1px solid #ddd;
    color:#666;
}

.followup{
    background:#e8f5e9;
    padding:15px;
    border-radius:8px;
    margin-top:20px;
    font-weight:bold;
}

</style>
</head>
<body><div class="container"><div class="header">
    <h1>SMART DIGITAL PRESCRIPTION</h1>
    <p>Digital Healthcare Record</p>
</div>

<div class="patient-info">
    <div class="card"><strong>Patient:</strong> Abhishek Kumar</div>
    <div class="card"><strong>Age/Sex:</strong> 25 / Male</div>
    <div class="card"><strong>Doctor:</strong> Mr. Sanish Kumar</div>
    <div class="card"><strong>Date:</strong> 03/06/2026</div>
    <div class="card"><strong>Diagnosis:</strong> Hyperthermia</div>
</div>

<h2 class="section-title">Medicines</h2>

<div class="medicine">
    <h3>Medicine 1 - Paracetamol</h3>
    <p><strong>Dose:</strong> 500-650 mg</p>
    <p><strong>Timing:</strong> Every 6 hours as needed for fever</p>
    <p><strong>Food:</strong> After Food</p>
    <p><strong>Duration:</strong> 3-5 days or as prescribed</p>
</div>

<div class="medicine">
    <h3>Medicine 2 - Ibuprofen</h3>
    <p><strong>Dose:</strong> 200-400 mg</p>
    <p><strong>Timing:</strong> Every 8 hours if fever persists</p>
    <p><strong>Food:</strong> After Food</p>
    <p><strong>Duration:</strong> 3-5 days or as prescribed</p>
</div>

<div class="medicine">
    <h3>Medicine 3 - Oral Rehydration Solution</h3>
    <p><strong>Dose:</strong> 200-250 mL frequently/as needed</p>
    <p><strong>Timing:</strong> Any Time</p>
    <p><strong>Duration:</strong> Until hydration is restored</p>
</div>

<h2 class="section-title">Special Instructions</h2>

<ul>
    <li>Keep hydrated</li>
    <li>Take proper diet</li>
    <li>Complete full course of medication</li>
</ul>

<div class="followup">
    Follow-up Date: 05/06/2026
</div>

<div class="footer">
    <p>Generated via Smart Digital Prescription System</p>
</div>

</div></body>
</html>
