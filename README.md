# I'm purple to demonstrate I can be custom styled

I'm only purple on the actual render website, not in the preview.

This file file serves as your book's preface, a great place to describe your book's content and ideas.

Here is some test edits.

I'm release-0.0.1

<button id="download-pdf">Download PDF</button>

<script   src="https://code.jquery.com/jquery-1.12.4.min.js"   integrity="sha256-ZosEbRLbNQzLpnKIkEdrPv7lOy9C27hHQ+Xp8a4MxAQ="   crossorigin="anonymous"></script>

<script>
$('#download-pdf').click(function(){
  var selected = $('.versions-select option:selected');
  var version = 'master';
  // var versionText;
  if (selected.length) {
    version = selected.val();
    // versionText = selected.versionText();
  }
  window.location.href = 'https://www.gitbook.com/download/pdf/book/sibyl229/testing/v/' + version;
  console.log(version);
});
</script>
