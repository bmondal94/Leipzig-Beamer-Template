# Leipzig University Beamer presentation template
Latex presentation template for Leipzig university.

## Notes
* **Use XeLatex or LuaLaTeX for compilation. pdfLatex compilation will not work becuse of font specification.** Please go through [overleaf custom font](https://www.overleaf.com/learn/latex/Questions/I_have_a_custom_font_I%27d_like_to_load_to_my_document._How_can_I_do_this%3F) if you want to know more about font specification.
* It uses `tikz` for the background images.
* The footnotes will be added from the bottom. If you want to pull the footnotes towards red-black margin line then use `\addfootspace{}` at the end of the `\frame{}`.
* `\addfootspace{}` actually adds an additional vacant footnote (without counting that vacant footnote).
* To add more foot space add more `\addfootspace{}`. Don't do `\addfootspace{\vspace{1cm}}`.
* If you want to make any other page layout like `outline` page then add `\SpecialPageLayout` before that particular slide.
* Use `\GroupLogo{logo-path}` to add department or group logo.

## Overleaf template
The Overleaf template is available here: [Leipzig Beamer Template](https://www.overleaf.com/latex/templates/leipzig-beamer-template/vxzvtsfytgcj)

## Acknowledgements
* The author would like to thank Victor Jüttner from Leipzig University for sharing his contribution to the project.

## Disclaimer
This project is a personal initiative, under open source code. There are no connections with the university officials yet. For any comments and suggestions please contact to badalmondal.chembgc@gmail.com .
