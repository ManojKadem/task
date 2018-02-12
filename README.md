# task
#!/usr/bin/python
This is the assignment built in the http://www.apache.org/licenses/LICENSE-2.0 It is provided here for reference for the task.

#Purpose
To build a blog post API.
Create a repository on Github,and add the code necessary to provide an API, included a copy of the database in your repository.
rePostId = re.compile("^\spostId\s:\s*(\d+)\s*$", re.I | re.M)

#System Requirements
'unicode' exists, must be Python 2.

#Installation
The scope URL for read/write access to a user's blogger data

    scope = 'https://www.googleapis.com/auth/blogger'
Create a flow object. This object holds the client_id, client_secret,

    # and scope. It assists with OAuth 2.0 steps to get user authorization.

    # and credentials.

#Configuration
The apiclient.discovery.build() function returns an instance of an
API service object can be used to make API calls. The object is
constructed with methods specific to the blogger API. The arguments
provided are: name of the API ('blogger') version of the API you are using ('v3')
authorized httplib2.Http() object that can be used for API calls.

#Running Test
logger.debug("Running command: %s", " ".join(cmd))
if (os.name == "nt"):
self.check_output(cmd, shell=True)
else:
self.check_output(cmd)
html = self.open(htmlfile).read()
except Exception as e:
print(e)
