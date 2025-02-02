# DRF-schema-adapter

**DRF-schema-adapter**'s goal is to provide a toolset to help you create fully dynamic
clients from **[Django](https://www.djangoproject.com/)** and
**[Django REST framework](http://www.django-rest-framework.org/)**. Given the right
frontend tools it can even help you to build a full-fledge admin.

## Compatibility Matrix

**DRF-schema-adapter** is compatible with the following matrix

|                 | Py 3.8       | Py 3.9       | Py 3.10      |
| --------------- | ------------ | ------------ | ------------ |
| **Django 3.2**  | DRF 3.12+    | DRF 3.12+    | N/A          |
| **Django 4.0**  | DRF 3.12+    | DRF 3.12+    | DRF 3.12+    |
| **Django 4.1**  | DRF 3.12+    | DRF 3.12+    | DRF 3.12+    |

:warning: For Python 2.7 or Django 1.x support, use version 1.0 or prior
:warning: For Django Version 3.1 or prior, use version 2.x

## Installation

### With pip

`pip install drf-schema-adapter`

### From source

Within the source directory:

`python setup.py install`

## Demo application

You can see a demo application running at
[https://djembersample.pythonanywhere.com/](https://djembersample.pythonanywhere.com/).


## Table Of Content

### Tutorials

- [Quick Start](./cookbooks/basics/quickstart.md)
- [Getting started - Django only](./cookbooks/basics/endpoints.md)
- [Getting started - Django and Ember](./cookbooks/basics/ember.md)

### How-To's

- [Create a custom metadata adapter](./cookbooks/topics/custom_metadata_adapter.md)
- [Create a custom export adapter](./cookbooks/topics/custom_export_adapter.md)
- [Use custom viewsets](./cookbooks/topics/viewsets.md)
- [Use custom serializers](./cookbooks/topics/serializers.md)
- [Actions without extra data](./cookbooks/topics/actions.md)
- [Actions with extra data](./cookbooks/topics/wizards.md)

### Specifications

- [drf_auto_endpoint](./drf_auto_endpoint/index.md)
- [Provided Metadata adapters](./drf_auto_endpoint/metadata.md#adapters)
- [export_app](./export_app/index.md)
- [Provided export adapters](./export_app/index.md#adapters)

### More

- [Code of Conduct](./COC.md)
- [More about Metadata](./drf_auto_endpoint/metadata.md)
- [More about `Endpoint`'s](./drf_auto_endpoint/endpoint.md)

---

License information available [here](LICENSE.md).

Contributors code of conduct is available [here](COC.md). Note that this COC **will**
be enforced.
