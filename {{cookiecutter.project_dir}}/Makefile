fmt:
	poetry run black . && poetry run isort .
check_fmt:
	poetry run black --check . && poetry run isort --diff .
lint:
	poetry run ruff .
test:
	poetry run pytest

.PHONY: test