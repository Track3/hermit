<!DOCTYPE html>
<html lang="{{.Site.LanguageCode}}">

<head>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<meta http-equiv="X-UA-Compatible" content="ie=edge">
	{{- with .Site.Params.themeColor }}
	<meta name="theme-color" content="{{.}}">
	<meta name="msapplication-TileColor" content="{{.}}">
	{{- end }}
	{{- partial "structured-data.html" . }}
	{{- partial "favicons.html" }}
	<title>{{.Title}}</title>
	{{ range .AlternativeOutputFormats -}}
		{{ printf `<link rel="%s" type="%s" href="%s" title="%s" />` .Rel .MediaType.Type .Permalink $.Title | safeHTML }}
	{{ end -}}
	{{ $style := resources.Get "scss/style.scss" | resources.ExecuteAsTemplate "css/style.css" . | toCSS | minify | fingerprint -}}
	<link rel="stylesheet" href="{{ $style.Permalink }}" {{ printf "integrity=%q" $style.Data.Integrity | safeHTMLAttr }} crossorigin="anonymous">
	{{- block "head" . -}}{{- end }}
	{{- range .Site.Params.customCSS }}
	<link rel="stylesheet" href="{{ . | absURL }}">
	{{- end }}
	{{- if templates.Exists "partials/extra-head.html" -}}
	{{ partial "extra-head.html" . }}
	{{- end }}
</head>

<body id="page">
	{{ block "header" . -}}{{ end -}}
	{{ block "main" . -}}{{ end -}}
	{{ block "footer" . -}}{{ end }}

	{{ $main := resources.Get "js/main.js" -}}
	{{ if .Site.Params.code_copy_button | default true -}}
		{{ $codeCopy := resources.Get "js/code-copy.js" -}}
		{{ $script := slice $main $codeCopy | resources.Concat "js/bundle.js" | minify | fingerprint -}}
		<script src="{{ $script.Permalink }}" {{ printf "integrity=%q" $script.Data.Integrity | safeHTMLAttr }} crossorigin="anonymous"></script>
	{{ else -}}
		{{ $script := $main | minify | fingerprint -}}
		<script src="{{ $script.Permalink }}" {{ printf "integrity=%q" $script.Data.Integrity | safeHTMLAttr }} crossorigin="anonymous"></script>
	{{ end }}

	{{- partial "analytics.html" . }}
	{{- if templates.Exists "partials/extra-foot.html" -}}
	{{ partial "extra-foot.html" . }}
	{{- end }}
</body>

</html>
