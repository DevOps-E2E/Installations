
# Installation Steps for Java on Ubuntu 22.04

## Update package list
<div>
    <pre id="codeBlock1">sudo apt update</pre>
    <button onclick="copyToClipboard('codeBlock1')">Copy</button>
</div>

## Install default JRE
<div>
    <pre id="codeBlock2">sudo apt install default-jre</pre>
    <button onclick="copyToClipboard('codeBlock2')">Copy</button>
</div>

## Install default JDK
<div>
    <pre id="codeBlock3">sudo apt install default-jdk</pre>
    <button onclick="copyToClipboard('codeBlock3')">Copy</button>
</div>

## Check Java version
<div>
    <pre id="codeBlock4">java -version</pre>
    <button onclick="copyToClipboard('codeBlock4')">Copy</button>
</div>

## Check Javac version
<div>
    <pre id="codeBlock5">javac -version</pre>
    <button onclick="copyToClipboard('codeBlock5')">Copy</button>
</div>

<script>
function copyToClipboard(elementId) {
    var text = document.getElementById(elementId).innerText;
    navigator.clipboard.writeText(text).then(function() {
        alert('Copied to clipboard');
    }).catch(function(err) {
        alert('Failed to copy text: ', err);
    });
}
</script>
