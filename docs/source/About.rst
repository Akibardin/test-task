About
==============================================


.. py:function:: person.get_last_job()

   Return a list of previous jobs.

   :param kind: Optional "" of ingredients.
   :type kind: list[company] or None
   :return: The ingredients list.
   :rtype: list[company] 

   Example
.. code-block:: python
   :linenos:
   :emphasize-lines: 1-5

      import HeadHunter as platform

      person = platfrom.get_cv(uid='Kibardin Anton')
      print(person.get_job_list())

      #output ->
      [ 
         'Rostelekom IT': {
            'Job Title': 'Hadoop DevOps',
            'Start Date': {
               'year': 2022,
               'month': 10
            }
            'End Date': 'present',
            Skills: [
               'Ansible',
               'Docker',
               'CentOs/RHEL',
               'Bash',
               'Hadoop',
               'HAProxy',
               'Prometheus',
               'Git',
               'Jenkins',
               'Python'
            ]
         }
      ]