document.addEventListener("DOMContentLoaded", function(event) { 
    chrome.storage.sync.get(['options'], function(result) {
        document.body.innerHTML = generateMarkup(result.options);
      })
    
});
