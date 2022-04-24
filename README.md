# Abra configurações do vscode, abra o settings.json, e cole o codigo abaixo


{
    "diffEditor.wordWrap": "on",
    "files.autoSave": "afterDelay",
    "editor.wordWrap": "on",
    "explorer.confirmDelete": false,
    "liveServer.settings.donotShowInfoMsg": true,
    "explorer.confirmDragAndDrop": false,
    "editor.fontSize": 15,
    "workbench.colorTheme": "OM Theme (Default Dracula Italic)",
    "workbench.iconTheme": "material-icon-theme",
    "thunder-client.codeSnippetLanguage": "js-fetch",
    "workbench.startupEditor": "none",
    "editor.cursorStyle": "line-thin",
    "redhat.telemetry.enabled": true,
    "javascript.updateImportsOnFileMove.enabled": "always",
    "bracket-pair-colorizer-2.depreciation-notice": false,
    "liveServer.settings.donotVerifyTags": true,
    "[vue]": {
        "editor.defaultFormatter": "octref.vetur"
    },
    "vs-kubernetes": {
        "vscode-kubernetes.kubectl-path.linux": "/home/castro/.vs-kubernetes/tools/kubectl/kubectl",
        "vscode-kubernetes.minikube-path.linux": "/home/castro/.vs-kubernetes/tools/minikube/linux-amd64/minikube",
        "vscode-kubernetes.helm-path.linux": "/home/castro/.vs-kubernetes/tools/helm/linux-amd64/helm"
    },
    "cSpell.language": "en,pt-BR",
    "cSpell.userWords": [
        "Usuario"
    ],
    "window.zoomLevel": 0,
    "python.languageServer": "Pylance", // ms-python.vscode-pylance
    "python.testing.unittestEnabled": false, // ms-python.python
    "python.testing.pytestEnabled": true,
    "python.testing.pytestArgs": [], // -x to bail
    "python.linting.flake8Enabled": true,
    "python.linting.mypyEnabled": true,
    "python.linting.pylintArgs": [
      "--load-plugins=pylint_django",
      "--errors-only"
    ],
    "python.formatting.autopep8Args": ["--indent-size=4"],
    "python.defaultInterpreterPath": "venv/bin/python",
    "[python]": {
      "editor.defaultFormatter": "ms-python.python", // ms-python.python
      "editor.tabSize": 4,
      "editor.insertSpaces": true,
      "editor.formatOnSave": true,
      "editor.formatOnType": true,
      "editor.codeActionsOnSave": {
        "source.organizeImports": true
      }
    },
    "[html]": {
      "editor.formatOnSave": true,
      "editor.defaultFormatter": "vscode.html-language-features",
      "editor.quickSuggestions": {
        "other": true,
        "comments": true,
        "strings": true
      }
    },
    "[django-html]": {
      "editor.formatOnSave": false,
      "editor.defaultFormatter": "vscode.html-language-features",
      "editor.quickSuggestions": {
        "other": true,
        "comments": true,
        "strings": true
      }
    },
    "files.associations": {
      "*.js": "javascript",
      "*.jsx": "javascriptreact",
      "*.xml": "html",
      "*.svg": "html",
      "*.html": "html",
      "django-html": "html", // batisteo.vscode-django
      "**/*.html": "html",
      "**/templates/**/*.html": "django-html",
      "**/base_templates/**/*.html": "django-html",
      "**/requirements{/**,*}.{txt,in}": "pip-requirements"
    },
    "emmet.includeLanguages": {
      "django-html": "html", // batisteo.vscode-django
      "javascript": "javascriptreact",
      "typescript": "typescriptreact"
    }
}
