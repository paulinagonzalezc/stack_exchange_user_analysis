# Stack Exchange User Growth Analysis

## Introduction

Stack Exchange is an internet forum website that allows users to post and answer questions about a variety of topics. The website releases data every three months that documents users, posts, tags, flags, votes, and a variety of other metrics.

This report details an analysis of the database providing novel insights into the data, it contains a triangulation of investigations centered around the change of individual users. Then we outline the conceptual schema of the data used in
the report. And after that we prove the normalization qualities of the data set. And finally we theorize the benefits and implementation of a graph based data model.

## Data Analysis & Insights

Stack Exchange relies on users of the platform for content through questions and answers. We hypothesize that users improve as community members as they use the site for longer. Our investigation will test this hypothesis via a triangulation of four experiments. First, we evaluate the quality of posts over time. Second, the improvement in response time as users post more is measured. Third, exploration of whether there are any trends in the topics users post about, over time, is performed. Finally, the connection between time on the site and the awards users receive is evaluated.
