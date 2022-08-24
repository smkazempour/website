---
layout:
permalink: /CV/
title: CV
nav: true
nav_order: 3
cv_pdf: CV.pdf
---

<object data="{{ page.cv_pdf | prepend: 'assets/pdf/' | relative_url}}" type="application/pdf" width="100%" height="100%">
    <embed src="{{ page.cv_pdf | prepend: 'assets/pdf/' | relative_url}}">
        <p>It seems your browser does not support PDFs. Please download the PDF to view it: <a href="{{ page.cv_pdf | prepend: 'assets/pdf/' | relative_url}}">Download PDF</a>.</p>
    </embed>
</object>
