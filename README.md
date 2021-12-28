# DAG Designer

## Introduction

As we all know, medical representatives (or Sales Representatives, as they are referred to in the
United States) are an integral part of the healthcare profession. They provide valuable insights
as to which new medicines have arrived in the market and thus serve as a key point of contact
between the pharmaceuticals and medical companies and healthcare professionals. Hence, these
reps are expected to increase the business for their companies and thus intelligent suggestions
need to be provided to these Sales Reps. These suggestions are based on certain triggers and are
coded in Excels. However, the coding mechanism in Excels is quite tedious and time consuming,
not to mention error prone all the same. This is where DAG Designer comes into picture. DAG
Designer allows the user to create logical flows specific to the need of the user to generate
suggestions and visualize the flow to get a better perception about it. This reduces the risk of
errors and helps to give the users a better insight to the complete flow as such. It basically serves
as a replacement for the mammoth excels thereby saving time and reducing the risks of errors by
providing a visual representation of what the user wishes to portray. This report covers the basic
architecture design of the project and dives into how a basic ‘flow’ is created, saved and executed
from scratch. The same mechanism can then be used to create flows for suggestion generation.

## Objective

- To design a tool that can provide users with a visual representation of the flow that they
  are creating thereby reducing errors.
- To provide a tool that would allow the users to save time by not coding the suggestion
  mechanism in lengthy excels but rather using specialized nodes in the DAG Designer
  for the same.
- Provide easy to handle mechanism to improve the overall efficiency of the application.

## Need

In the current scenario, the basis on which suggestions are generated to be then given to the sales reps are coded inside excels. These excels are mammoth in nature and are thus prone to error. Tracing down those errors in an excel is quite time consuming and inefficient all the same. Hence, the DAG Designer was thought of. The idea of DAG Designer was to provide visual aid to the users by entrusting them with specialised nodes to perform certain tasks. This allowed the users to be more efficient in their work since the errors were reduced and so was the time required to identify those errors, if any.

## Features

- `Visual Representation` : Various nodes are provided in the application to perform
  specified tasks which fall into categories such as Source Nodes, SQL Nodes, Action
  Nodes etc.
- `Easier execution mechanism` : Once the flow is created, saved and committed, a single
  button click allows the complete flow to execute. Highest level of abstraction for the end
  user.
- `Customizable` : Based upon the user preferences, the application allows the user to
  customize the way in which the flow execution takes place.

## Benefits

- `Less error prone` : A visual representation of the nodes allows the complete application
  to be error free as compared to the scenario wherein suggestion generation was coded
  inside lengthy excels
- `Time Saving` : Less errors would mean less time spent in finding those errors. Thus, this
  would allow for less time spent on error hunting and more time utilization for
  constructing and executing logical flows.
- `User Friendly` : With state of the art UI, the DAG Designer application is user friendly by
  providing the users a rich experience in terms of interaction with the application.
- `Two-step authentication` : The details of the configuration used by an agent to execute
  flows is tokenized providing the user with an extra level of security.

## Details

You can find specific details in the below URLs

- [Project Details](final-report.pdf)
- [Project Presentation](final-presentation.pdf)
