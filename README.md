# I'm purple to demonstrate I can be custom styled

I'm only purple on the actual render website, not in the preview.

This file file serves as your book's preface, a great place to describe your book's content and ideas.

Here is some test edits.

[pdf](https://www.gitbook.com/download/pdf/book/sibyl229/testing/v/release-0.0.1)

<button id="download-pdf">Download PDF</button>

<script   src="https://code.jquery.com/jquery-1.12.4.min.js"   integrity="sha256-ZosEbRLbNQzLpnKIkEdrPv7lOy9C27hHQ+Xp8a4MxAQ="   crossorigin="anonymous"></script>

<script>
alert('aaa');
$('#download-pdf').click(function(){
  var v = $('.version-select option:selected').value();
  alert(v);
});
</script>