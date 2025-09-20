# Python Codebases to Study

Learn from some of the best Python projects in the world. Studying these codebases will help you understand production-quality code, architecture patterns, and best practices.

## 🐍 Web Frameworks

| Repository | Stars | Focus | What to Learn | Key Files to Study |
| :--- | :--- | :--- | :--- | :--- |
| [**django/django**](https://github.com/django/django) | 76k+ | Full-stack web framework | ORM design, middleware, security, URL routing | `django/db/models.py`, `django/http/response.py`, `django/urls/resolvers.py` |
| [**pallets/flask**](https://github.com/pallets/flask) | 66k+ | Micro web framework | WSGI, extensions, minimal design, request handling | `src/flask/__init__.py`, `src/flask/app.py`, `src/flask/ctx.py` |
| [**encode/django-rest-framework**](https://github.com/encode/django-rest-framework) | 27k+ | REST APIs | Serializers, viewsets, authentication, permissions | `rest_framework/serializers.py`, `rest_framework/viewsets.py`, `rest_framework/authentication.py` |
| [**fastapi/fastapi**](https://github.com/fastapi/fastapi) | 65k+ | Modern web framework | Async support, OpenAPI, dependency injection, Pydantic | `fastapi/applications.py`, `fastapi/routing.py`, `fastapi/dependencies` |

## 🔧 Utilities & Libraries

| Repository | Stars | Focus | What to Learn | Key Files to Study |
| :--- | :--- | :--- | :--- | :--- |
| [**psf/requests**](https://github.com/psf/requests) | 51k+ | HTTP client | API design, exception handling, session management, adapters | `requests/models.py`, `requests/sessions.py`, `requests/adapters.py` |
| [**celery/celery**](https://github.com/celery/celery) | 22k+ | Distributed task queue | Message brokers, concurrency, task scheduling, result backend | `celery/app/base.py`, `celery/worker/worker.py`, `celery/backends` |
| [**pandas-dev/pandas**](https://github.com/pandas-dev/pandas) | 41k+ | Data analysis | Data structures, performance optimization, indexing, IO operations | `pandas/core/frame.py`, `pandas/core/indexing.py`, `pandas/io` |
| [**sqlalchemy/sqlalchemy**](https://github.com/sqlalchemy/sqlalchemy) | 8k+ | SQL toolkit | ORM patterns, query building, connection pooling, dialect system | `lib/sqlalchemy/orm/query.py`, `lib/sqlalchemy/engine` |

## 🤖 Machine Learning & AI

| Repository | Stars | Focus | What to Learn | Key Files to Study |
| :--- | :--- | :--- | :--- | :--- |
| [**tensorflow/tensorflow**](https://github.com/tensorflow/tensorflow) | 180k+ | ML framework | Graph computation, autodiff, kernel design, distributed training | `tensorflow/python/ops`, `tensorflow/core/kernels`, `tensorflow/python/keras` |
| [**scikit-learn/scikit-learn**](https://github.com/scikit-learn/scikit-learn) | 58k+ | ML library | Algorithm implementation, API design, validation, preprocessing | `sklearn/ensemble`, `sklearn/model_selection`, `sklearn/preprocessing` |
| [**huggingface/transformers**](https://github.com/huggingface/transformers) | 120k+ | NLP library | Transformer architecture, model loading, tokenization, pipeline design | `src/transformers/models`, `src/transformers/tokenization`, `src/transformers/pipelines` |
| [**pytorch/pytorch**](https://github.com/pytorch/pytorch) | 74k+ | ML framework | Tensor operations, autograd, C++ extensions, distributed training | `torch/nn/modules`, `torch/optim`, `torch/distributed` |

## 🚀 How to Study These Codebases

1.  **Start with the documentation** - Understand what the project does and its architecture
2.  **Look at the tests** - Tests show expected behavior and usage patterns
3.  **Study the issue templates and PRs** - See how the community contributes
4.  **Focus on one module at a time** - Don't try to understand everything at once
5.  **Run the code locally** - Experiment with modifications and see what happens
6.  **Read the commit history** - Understand how the code evolved over time

## 📚 Learning Resources

- [**Reading Great Code**](https://wiki.python.org/moin/ReadingGreatCode) - Python Wiki guide
- [**How to Read Source Code**](https://selftaughtcoders.com/how-to-read-source-code/) - Practical guide
- [**Code Review Guidelines**](https://google.github.io/eng-practices/review/) - Google's engineering practices

---

**Tip:** Start with smaller, well-documented projects like `requests` or `flask` before tackling larger codebases like `django` or `tensorflow`.
