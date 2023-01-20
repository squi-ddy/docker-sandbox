# Docker Sandbox
(originally made for IO question judging)

## Setup
1. Install `pipenv` (virtual environment manager)

```
pip install --user pipenv
```

2. Install dependencies via `pipenv`

```
pipenv install
```

3. Activate the virtual environment

```
pipenv shell
```

4. Run `docker/judging-image.py` to make the judge image

```
cd docker
python judging-image.py
```

5. (optional) Test the sandbox

```
cd sandbox
python sandbox.py
```

## Usage
Run `validator.py` and provide a filename to test.
It will judge the code for you.



