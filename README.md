# Homework1

## 哪些屬性對於惡意程式分類有效？

1. feature section_names_.tls (0.013411)
2. feature ent_q_diffs_mean (0.011097)
3. feature ent_p_7 (0.008002)
4. feature ent_q_diff_diffs_2_max (0.007035)
5. feature Img3 (0.006078)
6. feature misc1_unableto (0.006050)
7. feature dw_por (0.005857)
8. feature TlsAlloc (0.005746)
9. feature LoadLibraryW (0.005639)
10. feature Unknown_Sections_lines_por (0.005220)

## 哪些屬性對於惡意程式分類無效？

1. feature wvsprintfA (0.000000)
2. feature __vbaRecAnsiToUni (0.000000)
3. feature misc_installdir (0.000000)
4. feature ---Seperator (0.000000)
5. feature GetSaveFileNameA (0.000000)
6. feature lstrcmpiW (0.000000)
7. feature __vbaAryMove (0.000000)
8. feature fdivp (0.000000)
9. feature GetWindowTextLengthA (0.000000)
10. feature SetDIBColorTable (0.000000)

## 用什麼方法可以幫助你決定上述的結論？

使用Random Forest

## 透過Python哪些套件以及方法可以幫助你完成上面的工作？

pandas (read data) & sklearn (random forest) & numpy (standard deviation)